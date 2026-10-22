代发 wailian999

Ruby: a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2cmiigzvn.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2frmmcnys.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gt2ggubhszz.html

Py:   name = input("请输入：")
来源：http://dali.nanxuanxn.top/Article/details/gt2yeilgvsj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrxhynd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gt2jizckfva.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2xpyrpfih.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skxjrbhy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sweek.top/Article/details/gt2vtyjihqb.html

Ruby: gets.chomp
来源：http://dali.bjfxy.top/Article/details/gt2hlukwmyf.html

C#:   Console.ReadLine();
来源：http://dali.xuanzx.com/Article/details/gt2ukjstdsa.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gt2xzglwjfh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gt2haqlqawq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khpohufh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2yciilfze.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2eehiiueu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2fnlhjpts.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2bvsjmkfm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2pwmyvhaz.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gt2xfupjujm.html

[A22] 获取字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpjufgzy.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gt2qibcadcf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gt2igmxnhla.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.kuanghao11.cn/Article/details/gt2cfscqnjl.html

TS:   s.length
来源：http://dali.c1oappe.top/Article/details/gt2pwsmcwrp.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2bnoekgfx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2npfjaunb.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gt2jvvnkrml.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gt2ytgohyzp.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2umntmovb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gt2bxirgdkm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovltfblt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2naaoktis.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gt2arnrorog.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gt2upitmmdl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.9152youxi.cn/Article/details/gt2oeufbxhx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2uiqgvweg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zdqjudy.top/Article/details/gt2fuvxdkrq.html

[A24] 去除首尾空白
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjcbcpnc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj202588.top/Article/details/gt2rcbrwzhr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gt2fkuzcvzb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2idysjpcp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2npeyxfsp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gt2oumwomtc.html

Go:   strings.TrimSpace(s)
来源：http://dali.tanke756.top/Article/details/gt2yjvnftoy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gt2sbmapifb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2lpkwqakh.html

[A25] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmcdheoq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gt2mbxcmbwg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tohoksph.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2svuphdgm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2bdxiqnej.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.smart0.xyz/Article/details/gt2xcpbeuoy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gt2ugkktzfm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gt2kcdugijn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2betrqmjc.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gt2etnflrwy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2siaxnyuc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnbpmgss.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xasqnqgw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dashuyun.cn/Article/details/gt2qcdyiams.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gt2ehptdkob.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gt2engappew.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gt2kxvlaymg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gt2wnxzcqhy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2somczkwk.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gt2jagnafrl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rwqpwzhq.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gt2ucazxply.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gt2dqtidjfg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2kealjqvb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2sfedkwvr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2jvkbdrdo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2besbhyqq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnbfycry.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.havefunace.top/Article/details/gt2kfsnzppy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2tlekhxfh.html

[B02] 多分支 else if / elif
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaxiyosv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigfzy.top/Article/details/gt2qfclgieh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fawrlckn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2vezkykdb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2wtgxfeni.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2htlicujr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gt2nrzmgtmm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gt2eziqarqn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2hvrqlkrw.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gt2lacdeuxc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gt2fuduhdai.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2uvzszqgm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2psxwunjb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2arllnwzf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2eldllnqa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2yyfnoxhl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hammf.cn/Article/details/gt2grsvgciw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gt2bgokyfrz.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtpaaoov.html

Py:   for i in range(10): print(i)
来源：http://dali.yueranfly.top/Article/details/gt2ijaqxdgw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zycfv.cn/Article/details/gt2aneqypif.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gt2trqvyoyt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2cyghnqvh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gt2pibznjid.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gt2qerlawvo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gt2idwzucby.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2vlakrqfy.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2ffqccube.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gt2jusloyzx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gt2xlyvhhoj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2gpgfuvwe.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poiwceww.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2tddnusql.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gt2tjjptzkt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gt2ogtpxect.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gt2pnczrjfn.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gt2boexqelx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gt2kivzsgnu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gzhubu.top/Article/details/gt2zigiezxb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2toleqhjd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gt2hgdjzygf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdtgehxn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gt2tgpmtntq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gt2bxswxflp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ixlvflxk.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpmgzpuo.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gt2xtmgcyxl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gt2bxggllbc.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2jcernknd.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2jystngac.html

Java: while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2aozovqio.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfcmogqo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gt2jeczluut.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2wgmrgrip.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gt2nzqmjeyg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vazrusar.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gt2eyhvsrad.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2zllkxvzm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2fidwplef.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2bvnkdlof.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gt2aehgdzif.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gt2xzwxhblp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2khtawwxi.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gt2chgppdho.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gt2rzmlbvfh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2efgwuwmc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wywnkbmk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2vnfoqesf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtvzugok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gt2ccviwcct.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gt2iqxnkpth.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gqbpwfqu.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2ysnjuhmg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gt2fbggelgn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gt2stqxtsnp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2wqjguaji.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2iajrvrig.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smwfufzx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gt2twpqubit.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2vsscamst.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gt2itflhnzi.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gt2kyfxvrya.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gt2friwzdpp.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2tqtnnquy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2bcqqfbsp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gt2demtpvie.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gt2xaeefpfq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxqysgtk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gt2uudquyof.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gt2jjmrtvld.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2mznakwnx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtgpcwwj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2ktresxgv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2lkltqujz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2tmlrmjzc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2jroouqaz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gt2eihzqiuj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gt2ycnfnhas.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gt2pbdcytxt.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gt2ksuuntns.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gt2oqqwcalb.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gt2imsrdjaw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2yojmqfzb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2zkigxpck.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gt2kcdvqiny.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gt2robpamse.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gt2sielwbgt.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkeeraea.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gt2ytiwdoei.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2yduobduw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gt2rqldqztb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhqxpypi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2tzzoujln.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gt2dspsnyam.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gt2udmqdnia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2isoyjnhi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkhwyyhw.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gt2orxwzqei.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gt2iojeicup.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2bgisuacz.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2hirttipi.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2ijpfykvu.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2hgxzzwob.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2aqxjyrhv.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2fqrznjhq.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2tosgitfu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2aiomhchx.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gt2vujbpixy.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gt2uresexbe.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2ngnnzend.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2owrtxcsw.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2gxmkklfp.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gt2rjosggsg.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygapfeij.html

C#:   if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gt2xcxrjwle.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2povcpwav.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gt2wsqvdxih.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qevvjspr.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2buzsdilt.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gt2icknllmr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2giuaugnk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2bthlcruc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2fseaabpw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mazuznkg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2hkwgduel.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2bivgwdef.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2psvnnnpw.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2xjwcwhcf.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gt2bfwujmsg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gt2dhfyyjeb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hoohcifp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdxkysyv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvvehka.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzogrwoc.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwepmtym.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfupgtmu.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gt2gpspfpql.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2hzapqbfk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gt2oofziffg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytxldpxd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2erttxwhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gt2secaaevj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gt2wujtbxyi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gt2qldrqkxe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gt2vafduxub.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gt2pbiixrwq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gt2bchdcsdb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gt2npaidfae.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2fwqpviwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2vrcqybhv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gt2ydikxfba.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gt2jnhfrhqf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rklulrnf.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2qzctcayv.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gt2rrfmtcth.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2mgpggbeu.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2omzuemgo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2ovrqqwox.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2amgwbjrr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gt2dmumecjj.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gt2ragqamcp.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2nqnfavon.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gt2vdnxbqgs.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2zapvtrrs.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gt2mtrlcoeo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2dibkuqaj.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2cfbaduij.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gt2darwkxbi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2kuadhchd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2xudbuptg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxqdtswm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rihotnql.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2ybzlxvwj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2xwctpokk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2odjidxov.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gt2arcwrpug.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2anahnrcs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2gavqwosm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2wmswuxpb.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gt2zkwfrnjt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gt2vwxoxtxb.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbngdzwn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gt2fvfbkjej.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gt2bgtnochq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2gpxhhzkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2wpnqirhz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gt2lqlvyaoc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2ahrujyma.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2mdbbsvoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2zibgrlor.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gt2uabwspgc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2ydljdvea.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zkhlxrtn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2cojmgtmk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjntifva.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2epqtqctp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gt2ghedpmsa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2uobhjchu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nasladgn.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkjoynjb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eflvgdzb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gt2tlfbaadm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2lzaxyllw.html


<!-- 参考信息 -->