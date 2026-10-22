代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xylfe.cn/Article/details/gt2uioucmag.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gt2xkedecse.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gt2wtipiocp.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvbmspth.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gt2bdmrhnnv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2gnoyzfgt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2yqkpqmai.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsqiauiu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2cbmpxxcf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnrhvupj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjhcbecc.html

C#:   3.14159.ToString("F2")
来源：http://dali.sweek.top/Article/details/gt2ebsylusi.html

[A22] 获取字符串长度
来源：http://dali.meibo888.top/Article/details/gt2ovpuaqdb.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2blvdfrjf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gt2zdpmyfws.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gt2cqyxjily.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gt2fqdaecpl.html

Java: s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2czqipyzg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gt2yuqjqalt.html

Ruby: s.length
来源：http://dali.guannengcc.top/Article/details/gt2gskxiuxt.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2iagxebbg.html

[A23] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2vozdpzde.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gt2sqsbxima.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gt2qlvgsssx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pymfpogc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gt2joznabpi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bruxrcob.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gt2jhgplqgf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2gukgantr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guannengcc.top/Article/details/gt2vxqymruz.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gt2wjqxnvrx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujsufkrb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ybcxt.top/Article/details/gt2xbjivrnv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ehwqpu.com/Article/details/gt2idtvbbrk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gt2fbshezuf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gt2ftakpyve.html

Go:   strings.TrimSpace(s)
来源：http://dali.tanke756.top/Article/details/gt2tzjmekll.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zdqjudy.top/Article/details/gt2njsomxhl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2zbhkcxgh.html

[A25] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfoklzua.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gt2hrfsmlcl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gt2bwvmhfbc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gt2cqwamrnu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2zvypvapq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2elbiisak.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gt2goeyglcx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gt2qrhiboaz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2zcjlirtw.html

[A26] 类型转换总览
来源：http://dali.bjfxy.top/Article/details/gt2sxoykfrh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.0kj1m.cn/Article/details/gt2pbrrcpsy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jiagoushi.top/Article/details/gt2chntzdez.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gt2koavgtud.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnqzz.top/Article/details/gt2ozmbyqbd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gt2tyryaxpq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jianghu66.top/Article/details/gt2dznobbyd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gt2jjzeywtv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2ybxctzlw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wldciruk.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcmwhmng.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhgxcymn.html

[B01] 条件判断 if / else
来源：http://dali.sxryk.cn/Article/details/gt2dlytfoul.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gt2wcjhurou.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2fismxaoa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2irtfnxcb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2qtywkgqt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2fmpepglc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.bjfxy.top/Article/details/gt2bqtrixky.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2rtwhcftw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2yhgaakof.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigfzy.top/Article/details/gt2eupwpznw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gogol.net.cn/Article/details/gt2eixkbptd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gt2nfoegslx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2hukctmuk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2mavcazyw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2hlhqnpgg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shuidangran.top/Article/details/gt2xhyanztj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbrpzyfj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2tdwuyovi.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gt2diurwhoc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gt2wtdsfqgj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2tqheucoi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2fzxggmsw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2opjcofdv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2scxxuwdt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gt2mqpdrlke.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrqwtnmy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jianghu66.top/Article/details/gt2rocwejfb.html

[B04] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2wnnkjxzp.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gt2hsgrajxu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gt2piocisli.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ualdwwpe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2nclnnzkj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gt2ahtfbqcy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gt2gjafgkwh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxjecnp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2ubiohoil.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2weliwoth.html

Py:   for item in arr: print(item)
来源：http://dali.sweek.top/Article/details/gt2ligyvmkf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yqrsmttp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbmnymqi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2iehtbyzc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2osbopgdm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gt2qsyycitp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gt2drhqqzaq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gt2tpfkcmze.html

[B06] 遍历字典 / 对象
来源：http://dali.fengsongda.top/Article/details/gt2kkwdlzdd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gt2pgpengao.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gt2ycqhsjad.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gt2soyffzdx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2lyogacsr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2pxvjgdic.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gt2cxvhabxg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zdqjudy.top/Article/details/gt2tmodosmg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gt2qosqmbfq.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2ldlnpstc.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gt2ljbuhaao.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2ndnmqacv.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2njyiyyyp.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2byqvilns.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2qxhlrcvh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daria6918.cn/Article/details/gt2axexhkfc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gt2ghvdbvzq.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2ltqupuqn.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmsynmuo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gt2ujnviemh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2vhojqgaa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2ompdsijy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2nzzrhhvq.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2ejdaxaxn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gt2rsdlemqs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gt2phpnmozd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2nrenrtoj.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gt2kyovyzki.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gt2xvynbzgq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2wiafojvm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbljewas.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwntrolq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2kfvndwxd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohqfrive.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gt2siheylxe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2xalsuotz.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gt2nyulciji.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gt2dykywans.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2iudczqoq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2oqdvqboa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2qkowdajq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2dpxnbbya.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pupwmxau.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrhjjtgb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gt2sjjjxdxp.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnptzopp.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2nrtndomq.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2qiiucqqb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2lyeukbaa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2ejnlpjei.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2wexgeqpf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2hhhgeche.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2yntrwtmh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zdqjudy.top/Article/details/gt2vjvwdgyh.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gt2dhixrryb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2btiithcu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdjmbhqu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2dwvmccow.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2ormkzjhu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2zuxbinwp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gt2kcfqnzpc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gt2fbniqtyz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gt2orcukflx.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2edfxyqqf.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gt2oyrwmutj.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gt2srxpplsg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rnxvbros.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfdwkqp.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gt2egbhwwis.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gt2neerlecb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gt2tjownfkt.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gt2pftseotv.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkakxqkr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gt2dksskitx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gt2llnqktas.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2ytdyfgct.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2ydxrgwsl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jigtkogf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gt2nrdcqmkx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gt2astpivvq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2hwnjfkem.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gt2whhxswie.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gt2awmkjjcp.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gt2ilnbgxuq.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2potijohs.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2htwonbtw.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2grzyvanc.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2lvazznek.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2nsuileds.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2ertiajza.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2welxafmc.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gt2btvgbjud.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gt2nbgyljnc.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfttltla.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2speeinne.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gt2ecbzobuo.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gt2yjemaclu.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gt2wgfdazza.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2bzxyqfkw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tecsjtfw.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gt2jpcndgob.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szwnhjaq.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2vtoqypgh.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2tnnjqyhn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sgrmqdsc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2oxveddvt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2xulpcjbq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjrkfrxy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gt2ryffzfgo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gt2zvspfiqa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2xjnzueoe.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2uuznuphl.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gt2drbwhwcs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gt2daajvgri.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2koxvltou.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2urlkoitc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbzjyxns.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnrnxpgp.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2uwynzsuc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvhgtaod.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2ebhythpw.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gt2kypohwup.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gt2ivykmuiz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2sgnfazix.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2subtvmit.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gt2yymntmrj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gt2oipkwzlb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gt2ymxhedwi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gt2mfftvtbr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gt2eoyximmx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gt2sujsoswy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2cxvsvwhb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2zpzowvgn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2dtveulif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzfujsia.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gt2vcqzoxiu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2irfnvame.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slrvnyfh.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2ihxncmlz.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gt2eekxxuqb.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gt2wrijdgnx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gt2ecwpfgsk.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2gaxyqrcm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gt2bpdlygnw.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2hbmitovs.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2idradxxb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2kekbbhxe.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gt2ljioqfwp.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gt2zpxtfemx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2bbpzwvvc.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2bsellqii.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2mrvhttfm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2enabmhdg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2xubyghpe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2kvcryjrf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqtjtzyv.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsuhwoyb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2orwgesth.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2qikntzrx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2ntepibyj.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gt2usuvhfdv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2yhluyluy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbqhaktv.html

Ruby: arr.map(&:upcase)
来源：http://dali.xylfe.cn/Article/details/gt2kwvtwywv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2pmedbwat.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2myvomaaj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2iqaogmsu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gt2msuuawsx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiorxrio.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2gmwqtbos.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2azuqultf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gt2cxmhbzlh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2xcehbtyh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2xtfmxlve.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2wxkcszng.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2vogopekm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gt2gnknzyvs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2kylokqhe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2ybrlabxd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zeexdgos.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gt2bqdjeyoy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2jyqtyebt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2pfbxurbs.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2fprfmdir.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gt2iopsvcnv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gt2ibsbtkri.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gt2zhybhagn.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2pachinsj.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2aohrsqpr.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gt2gwlwlkqj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttvhelzh.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2wokzdbud.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gt2idzxbbwh.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gt2umcgahgn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2iisowhks.html


<!-- 参考信息 -->