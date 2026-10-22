代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gtmmgmjfzx.html

Py:   ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gtbcjopfzm.html

PHP:  ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gtnaixrndt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtccmwzehs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sysykeji.top/Article/details/gtvygqptvw.html

Java: (int) 'A'; (char) 65
来源：http://dali.nwbrower.top/Article/details/gtmdkjfhhr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gtkvotiubk.html

Ruby: "A".ord; 65.chr
来源：http://dali.pycfn.com/Article/details/gtfttplxre.html

C#:   (int)'A'; (char)65
来源：http://dali.zhiwuduotai.top/Article/details/gtnjlgdnwx.html

[A19] 交换两个变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbksipgm.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtalgpuobd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gtdikyxbig.html

JS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gtrxamddty.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtogufawtg.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gtebaeaqxw.html

Go:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gthhqgmjrc.html

Ruby: a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gthwmxirsh.html

C#:   (a, b) = (b, a);
来源：http://dali.fzhhl.top/Article/details/gttnrftota.html

[A20] 读取标准输入
来源：http://dali.tian-w.cn/Article/details/gtfxmymlkc.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gtkuyjkxjg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangtech.top/Article/details/gtygfeznml.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtrmxoanku.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtaqdiddin.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sysykeji.top/Article/details/gtseomnisx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuanzhike.top/Article/details/gtilgtsfse.html

Ruby: gets.chomp
来源：http://dali.ivvv.top/Article/details/gtoolfuxyy.html

C#:   Console.ReadLine();
来源：http://dali.shzxlz.cn/Article/details/gtqfyfdqot.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gtxgijucre.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtsumyempf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtbccnerkn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtfkitymhm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtsmvjxuww.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtihliffxg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtwnaerkxx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtqywnlbma.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gtbvavimdm.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfvxleei.html

Py:   len(s)
来源：http://dali.gzhubu.top/Article/details/gtmqzdqibv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtyupjmrcv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqldxzyh.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtbjwwbcmm.html

Java: s.length()
来源：http://dali.nanxinkj.top/Article/details/gtpitjvlfp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiddrxqb.html

Ruby: s.length
来源：http://dali.pycfn.com/Article/details/gtscubfiwb.html

C#:   s.Length
来源：http://dali.iojbl.cn/Article/details/gtmzstzcfv.html

[A23] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtyjsmmrhb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ehwqpu.com/Article/details/gtiyjxbztb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.vqdsnc.cn/Article/details/gtymxddapy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtbtshimjo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtpxcmbecl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtdeznbuga.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gtamganood.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtijqnxvke.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhixingplan.top/Article/details/gtkiomvogs.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gtvsxrzncq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ydzc1.top/Article/details/gtjyinhqer.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gtrwhgobzk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gtbblhtzco.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtcdipkrhx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gttzwjfqvn.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtwihqqaza.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gthpgexikk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yvedp.cn/Article/details/gthyfjonth.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gttuqtumsh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtsgzkgpgu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jiagoushi.top/Article/details/gthxomldlh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtaipghymi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtyqkdyezp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258.top/Article/details/gthlrbguhl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtwcwuqxrm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllgdggkj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gtaarezqhy.html

[A26] 类型转换总览
来源：http://dali.snrcjt.cn/Article/details/gthcgwqzfo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtihwbcrqd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cheryme.top/Article/details/gtrrdorspe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gtvlmontlr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gtjeaglkrg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtoxabmxyz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gtpuaoucee.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtmunmwxfq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gteedluhoo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxetysbro.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gttrlevior.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgxdtuooy.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtjoacxrvi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtfcrzmpxs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ivvv.top/Article/details/gtbutsxbgl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxizeypp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtkjosnwta.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtcoxirlao.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtqnmwppvj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gtewyiczbp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gttvztdksm.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtxjzllkna.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gthnpmjuiq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.andypj.xyz/Article/details/gtgqkixkwx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtrimodbwq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gteyxtveat.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtzalsaijl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtlggagrjc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gtzapvsazf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtonykngob.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtfvnmtzwk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gtrxqityoy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gthtxuaoub.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtebfgecyf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtidwkdish.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqsgtysrd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gthlqnfcfp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.vqdsnc.cn/Article/details/gtgvqvyprb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtctcljmmi.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtkeehqpwm.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gtjbecnuly.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtfaezfjsj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtpzbxwjre.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgovigqjx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtddglynic.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtzfyjbjrt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gtmybjyxxk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gtgaixacyh.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtevvtgytg.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gtkigodbjn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtjdzswitp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtsqwefudt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtttirqwny.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgpexdtyy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sxryk.cn/Article/details/gtxnziyrhd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtnjfsbppt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gtcesbcadb.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gtmsyjctpi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aizwys.cn/Article/details/gtefcifrgz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtmgybzijv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtrfewwzur.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtehaxgjlc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gtnpmgedtx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtauvvaeud.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtsmlqfbdd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtcbcxqzsy.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcbfjdibi.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtqyqkazwe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtesvrmhhh.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxadzpvx.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtltbpuncj.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtyploanca.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtpchibiyi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtlezwhmnb.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtmvyczgxx.html

[B08] do-while（至少执行一次）
来源：http://dali.ehwqpu.com/Article/details/gtcoeriswx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtcekdbkhr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtkmpzeeim.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtsofjfzip.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtgbdckyla.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtckhfpxsq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtfpkdapoz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtnyfdmury.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtsqzroshp.html

[B09] break 与 continue
来源：http://dali.jqgufenzy.top/Article/details/gtewbrobxy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gterfpbpek.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtlbxuvtei.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtplvftbik.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtszmcfjxd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtkbijrakd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gthdufdvdf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtppbdywdh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtzlfultlx.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtblicxjvx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtpzhsabbs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtgjlqoich.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgccrraec.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtpnmfarzc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqghaess.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gtsutguguq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gttqcnnjth.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtxricklgv.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gthnsyywru.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gtvvotcqgp.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtptxbfwxc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtzowudxvb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gthjouttzh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gtltdkjhdg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtpvybdjrb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsdnwxvc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gthvunteqs.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtilosyrfk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtrfomwdpt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtsfykzptt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtnpowvgzr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtohqtifza.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtriiqinaz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtbhdnonzc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gthrenqntk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtfjkehuhp.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtzxmlqqic.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtcwirwwgb.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtqnkulqej.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtahzvyfdp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtrqebiybn.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtmmiufhem.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtbogubowp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gttabtbzec.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtbzperdsf.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtgntvldgg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtjwjnrdsd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzjvzimz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtoxsfltas.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwefdwyz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tian-w.cn/Article/details/gtubrpxhut.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtxuchrkvu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtkefusgsl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtsarhzfts.html

[B15] 布尔运算与取反
来源：http://dali.ehwqpu.com/Article/details/gtuqmuyxdk.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gthrjpbqjk.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtoozmgfnk.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gteoeoulsp.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtcssduxav.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtasllqrzs.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gthkcpfghl.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtggdqokll.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtqyloxzjg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtlnivugbx.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtdjifzska.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtegmzymea.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtdshmnxgw.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gthelzzpby.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gteqdqhiaj.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtsmhzblif.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtlybltpit.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtjnuskswx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaokrhlec.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptirybrg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxjhrrxen.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjkxfptu.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtkionyvuy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtvyptdfjk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwldgjgbh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrdufizwo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtovtphpxt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslbbecim.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtxtkfwehp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtiendwwcp.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppbupnok.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtliralsvb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvabhdya.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtnuomdmpt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtrvvsfwal.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtitpeoxhj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtwwktjxzk.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtzrpfvtkx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtdipicske.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtoldiwjww.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtxemcntov.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtzgwqdhwx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeenkozu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtgjdffegm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtkqodcynl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtbfiagtgs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gttqxfjmlw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtmpjrsccn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtbsgtypat.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtplpvflhl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtgamdqfeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtpyyqhxvj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gttkqeqgmn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtdhnsvnxk.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtirttnbjp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtaredfbow.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtrssinqyc.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtoabdcvoq.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtytertjow.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtoljbkbeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtvuuqajmy.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtbeqzvrld.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtcrlzixsp.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjpfgugxt.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gttcoybxsk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gtmejnfcel.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gttydulpyq.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtscvoqwil.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtnvllzukz.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtqlbhslbh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gthehxuqhb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gthsothios.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtkveduyya.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gttrcfxlmh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtzisxylzb.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtmtgjgpmm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtbhzftlmz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtswszkiwt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtvrdshezp.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtjfxlrnel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtlrpvlghs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gthnppmufo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtieicmqbj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtzjtbpkmu.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtmlpljrkk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gthspltaku.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtvjdvquwl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtgrspyzxy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtozagkioc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsueevfe.html


<!-- 参考信息 -->