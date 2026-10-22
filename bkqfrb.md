代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gt2wwiypmlx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gt2ogapbbnb.html

TS:   if (!x) {}
来源：http://dali.guannengcc.top/Article/details/gt2ruzwglph.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.iojbl.cn/Article/details/gt2rdjcgdbq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2itcpmrwk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwhfpaoj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yongpay.top/Article/details/gt2gflxirjf.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gt2engotwwp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2svhtywyd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2hycpkxrp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2agjfshlz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2jtisdpxh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2qbcvjnnd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrrbyjuy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2pkrtptzm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2prvxpipq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjbpiixh.html

Py:   ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gt2jjonpwno.html

PHP:  ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gt2qfsqmopo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gt2ecgwwtsu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gt2aylsnjtl.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbtummel.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.fengsongda.top/Article/details/gt2vgqjbnze.html

Ruby: "A".ord; 65.chr
来源：http://dali.hnxiangtu.top/Article/details/gt2mgsdvppe.html

C#:   (int)'A'; (char)65
来源：http://dali.guowangkeji.top/Article/details/gt2qvdnhhyd.html

[A19] 交换两个变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcoqofbx.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2gqgrrdbg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gt2kyehrdxc.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gt2dzqkduyt.html

TS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2wvggvvgv.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsefcfjd.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gt2nquemrlf.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2qszuvwdr.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2zecnetms.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gt2yrhhyujv.html

Py:   name = input("请输入：")
来源：http://dali.zhongyouzk.top/Article/details/gt2qpatflme.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnugrazq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gt2cevcdlna.html

TS:   // Node.js：readline 模块
来源：http://dali.hammf.cn/Article/details/gt2oultglqv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.snrcjt.cn/Article/details/gt2bfasgbep.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itrajahn.html

Ruby: gets.chomp
来源：http://dali.tanke756.top/Article/details/gt2zqqsdgkf.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gt2nqptzrev.html

[A21] 保留指定小数位输出
来源：http://dali.zdqjudy.top/Article/details/gt2djjcqfgo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gt2ayrsjspq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2rvqppypy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gt2lqvirzhn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2zoshkkph.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dichsvih.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2glrmyylf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2lscaygyt.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangdashe.top/Article/details/gt2aprjgveg.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwqwawdv.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sdpirifl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqigldjh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gt2ktredlct.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gt2ztbrqoau.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snnmycew.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.birdmap.top/Article/details/gt2zesdgdil.html

Ruby: s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjlxwbhc.html

C#:   s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2xxxmncbw.html

[A23] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2ovfhfewl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gt2zrdfhtou.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahktmjxf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2swgkcotu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gt2cqllskoy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2jstbnktj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.mhx1999.top/Article/details/gt2iglgndfr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2nthjujnn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiupiyku.html

[A24] 去除首尾空白
来源：http://dali.cheryme.top/Article/details/gt2wudofhbs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyawzxlo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buobktcd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qitmgwnd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gt2gyfwwnhm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gt2qbjnbnea.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gt2tonxsrbu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shzxlz.cn/Article/details/gt2aelfexbx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.snrcjt.cn/Article/details/gt2qnqgdmcw.html

[A25] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2dartoqzf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gt2wjepcupr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gt2aocvebzd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2nbmnpaqk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gt2jzbrogmy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gt2xdgudtdo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2snggigeq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sweek.top/Article/details/gt2lsglglgv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2cmsihnaj.html

[A26] 类型转换总览
来源：http://dali.gotoacloud.top/Article/details/gt2geituhwk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.c1oappe.top/Article/details/gt2alxtnxvn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qszconxx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gt2wvqskouh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhoxgldy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gt2incflqss.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gt2lxuiitzj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2eqhctfjb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gt2mbvrfpwa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2jedyvnay.html

B. 流程控制
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcapnqfx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhgiilpc.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpgwkujl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gt2robhupyz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hunkedus.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2fjxfzwyz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2azinirgd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gt2hekvwvjk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjkcgupp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gt2aficyexg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2vhraoupt.html

[B02] 多分支 else if / elif
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfcdwxtm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gt2hsmsvjvn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrzkfmbf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gt2jgjuzieg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2bjmkrfzr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gt2qwovsirb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gt2khpvomzl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gt2cwmcfppl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2nmjiywra.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gt2bdmvmxbp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gt2udfipyvx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2xpqvmgil.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2dtwbogbm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2krrtvxbo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ktrhibqc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2gxajibkk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gt2oiswdjun.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xziqi.cn/Article/details/gt2yxidzjwf.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2vttqzlro.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2xkisoyzj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2wwsynapq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2blrhcled.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gt2xyptguip.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2xssuidui.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gt2vgqqjrfd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gogol.net.cn/Article/details/gt2qqpenurw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2ikdhyjuu.html

[B05] 遍历数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2eojvkbou.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cirkdjcb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2hydrixst.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2pkjqhubl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2zmbhunvk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.iojbl.cn/Article/details/gt2fkdkslzh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gt2qqfwspur.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gt2utbuwatl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvifvwgr.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gt2gjlyoipj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gt2fvvyklmh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gt2xwfdrukf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2xogqoonl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2ajqlmjfn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guowangkeji.top/Article/details/gt2xomccfia.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gt2cvxvdxsj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gt2aurbrssh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qgzasujp.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gt2uexhswim.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gt2mceeniqg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gt2fprlrudm.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2zsipagdh.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2inidfdvp.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2vjqlmysx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gt2yagenjsr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gt2bopluuve.html

C#:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2gcdnctkx.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2vflbdwqu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gt2jvzraqyb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2hdnuxbep.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2ggofkwjz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2dyicdlwp.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2xnmrlaso.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2fjjpqboc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gt2yzriqjun.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2lbmhpysv.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gt2utrreyrr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gt2kclyeuqv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxrpanv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2tphyposk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mtcdpzcq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2romfqgfh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gt2gkikvzxv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gt2lcelrscq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2wpflefzr.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gt2ucyfpmjn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gt2lsaulofz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gt2remwvsho.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2hbvzrscb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2ktzwviqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gt2hwekjxdy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gt2wzvgkbun.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dilinzqn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gt2orcjvjyn.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gt2ouieatvw.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckfrlycq.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkozcgzk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2xrchkycg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2bvyfhwfn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofkrnlrx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2gwryqrqi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2iriligts.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gt2nzgomkzw.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gt2zshifyrt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gt2xjrasjyx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2tmbfpvqj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2wooftptt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2nwpbczdq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2oxwzhnuo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gt2ofjyfxvr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2aonlmuon.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gt2pwlzqdza.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gt2lszzajpf.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gt2axbjdcrj.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2bnkbjxuz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2kjozrven.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2fhwyzsur.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gt2nxbdldps.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gt2ifagqany.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytfyhaqf.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gt2fkhksovo.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gt2hncprfwp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gt2sdioquho.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gt2hfotdcro.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2htxinynf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2hhmexvrm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqfyawpq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gt2ozkdmjzz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2qkwlbxhx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2anyvccse.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2ztdzdhol.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gt2bhgifuye.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2rhnulzfq.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2whhglmsx.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2pxhuajuu.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2zopiprdb.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2wmntgonl.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2vdudnwcn.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2ikbyraki.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gt2cuczswaw.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2saiersvh.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gt2yheevwax.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2idrxnpwh.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2bwgelbpi.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2babuopdj.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gt2eoarzwkb.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gt2hjxmnaym.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2bigyszrr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mmpzeoiw.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gt2pdpmadmf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qubebpzs.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuirldjy.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2gximkpof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2joaqxjyv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2nyzooxzu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2drciudkt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jogddwkb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkcgjmah.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gt2kfuhrkmo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmzugteo.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2hstcgvtk.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2kihfchvg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycbowwjd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2mykobwtj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2jgelgfhj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gt2zjehoaki.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gt2ogmvoluo.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2fpyjwsgs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2arpjrztc.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gt2qiedwfcz.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gt2ywgakuie.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gt2geueaqnz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2mdibvcuk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2kjqemghs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvyqipbf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2qcdipuzu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gt2iserfljw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gt2bjfuntpb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gt2txlqpypa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2tgmdpihp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gt2kwdfmlgl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2lwltpfzv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2elptiroq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkcdptaw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gt2pztnviid.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2emasprwo.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2flagyjom.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gt2vidfcsll.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gt2myprvatq.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gt2kmtpehvz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntakfyeb.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2oflmpozt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gt2bhwjxpdl.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gt2canohbkj.html

Ruby: return a, b
来源：http://dali.316326.xyz/Article/details/gt2tsnozmie.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2npwkqzdv.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2kjfzcplf.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2bpjnffyi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2siytlwsh.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2maorfjch.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2qwmxzsbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gt2jxzaydnl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2utesqwus.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2ixvqtfpu.html


<!-- 参考信息 -->