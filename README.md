# テクノロジー（藤原） 11/1授業

```

shin4050:~/workspace $ pry
[1] pry(main)> num = 2
=> 2
[2] pry(main)>
[2] pry(main)>
[2] pry(main)> if num % 2 == 0
[2] pry(main)*   puts "偶数です"
[2] pry(main)* end
偶数です
=> nil
[3] pry(main)> puts "偶数です" if num % 2 ==0
偶数です
=> nil
[4] pry(main)> num = 1000
=> 1000
[5] pry(main)> if num >= 1500
[5] pry(main)*   puts "送料無料です"
[5] pry(main)* elsif 0 < num && num < 1500
[5] pry(main)*   puts "送料300円です"
[5] pry(main)* else
[5] pry(main)*   puts "入力が間違っています"
[5] pry(main)* end
送料300円です
=> nil
[6] pry(main)> num =2000
=> 2000
[7] pry(main)> if num >= 1500
[7] pry(main)*   puts "送料無料です"
[7] pry(main)* elsif 0 < num && num < 1500
[7] pry(main)*   puts "送料300円です"
[7] pry(main)* else
[7] pry(main)*   puts "入力が間違っています"
[7] pry(main)* end
送料無料です
=> nil
[8] pry(main)> num = rand 3
=> 1
[9] pry(main)> case num
[9] pry(main)* when 0
[9] pry(main)*   puts "吉です。"
[9] pry(main)* when 1
[9] pry(main)*   puts "凶です。"
[9] pry(main)* else
[9] pry(main)*   puts "大凶です。"
[9] pry(main)* end
凶です。
=> nil
[10] pry(main)> num = rand 3
=> 0
[11] pry(main)> case num
[11] pry(main)* when 0
[11] pry(main)*   puts "吉です。"
[11] pry(main)* when 1
[11] pry(main)*   puts "凶です。"
[11] pry(main)* else
[11] pry(main)*   puts "大凶です。"
[11] pry(main)* end
吉です。
=> nil
[12] pry(main)> def triangle(b, h)
[12] pry(main)*   result = b * h / 2.0
[12] pry(main)*   result  # 返り値は最後の1行
[12] pry(main)* end
=> :triangle
[13] pry(main)> triangle(11,9)
=> 49.5
[14] pry(main)> triangle11,9                                                 
SyntaxError: unexpected '\n', expecting &. or :: or '[' or '.'
[14] pry(main)> triangle 11,9
=> 49.5
[15] pry(main)> triangle(10,9)                                               
=> 45.0
[16] pry(main)> name=gets
imanishi 
=> "imanishi\n"
[17] pry(main)> name
=> "imanishi\n"
[18] pry(main)> name.chomp
=> "imanishi"
[19] pry(main)> 10.times do |i|
[19] pry(main)*   print i, ", "
[19] pry(main)* end  
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, => 10
[20] pry(main)> 10.times {|i| print i,", "}
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, => 10
[21] pry(main)> a = ["りんご", "みかん", "ぶどう"]
=> ["りんご", "みかん", "ぶどう"]
[22] pry(main)> a.each do |item|
[22] pry(main)*   puts "おいしい" + item + "だよ"  
[22] pry(main)* end  
おいしいりんごだよ
おいしいみかんだよ
おいしいぶどうだよ
=> ["りんご", "みかん", "ぶどう"]

```