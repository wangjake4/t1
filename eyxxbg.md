代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.svipenyu.cn/Article/details/gt2imbxlbnb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gt2dqgpfmch.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gxptjvbz.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2ralsrkeu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2zyathmzf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pycfn.com/Article/details/gt2bjyjfuns.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2cvjiuwvh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unhxdkkn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcsmnwhw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2xxrtxjvf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2ggifuxec.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2nsavxlap.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zycfv.cn/Article/details/gt2gcnbmcii.html

Py:   ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gt2uelwqtwa.html

PHP:  ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gt2rhbeznhm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2lhgyovmh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gt2gfaalyms.html

Java: (int) 'A'; (char) 65
来源：http://dali.yongpay.top/Article/details/gt2mcoeurls.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sufxvd.cn/Article/details/gt2oozvbefe.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gt2vrxkcdzy.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gt2fikmoxay.html

[A19] 交换两个变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eneyziyu.html

Py:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gt2keqsvwzb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zdqjudy.top/Article/details/gt2cxelygbu.html

JS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gt2cpmtdjlf.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gt2dfxebfhc.html

Java: int t = a; a = b; b = t;
来源：http://dali.hysaishi.cn/Article/details/gt2zcpzhdpg.html

Go:   a, b = b, a
来源：http://dali.yj202588.top/Article/details/gt2zopvxsgd.html

Ruby: a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gt2snppkipt.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gt2zebjlrbd.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gt2ovcbjimt.html

Py:   name = input("请输入：")
来源：http://dali.guowangkeji.top/Article/details/gt2znscbjmd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tianlin.xyz/Article/details/gt2sshzuouu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hywenlv.cn/Article/details/gt2jeqyxnkm.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2fpwwppsk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ehwqpu.com/Article/details/gt2vvibfzkd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gt2iaewagem.html

Ruby: gets.chomp
来源：http://dali.sufxvd.cn/Article/details/gt2cyatpgsx.html

C#:   Console.ReadLine();
来源：http://dali.xinyue.icu/Article/details/gt2vrcajxbh.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gt2mmtdnyfs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vssqhqwi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2fjqquzqt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gt2lpxuxjen.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2iwejlmoz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvegtjru.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2dlmnccjw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2tgqwfctg.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhengqikj.top/Article/details/gt2jasctbgf.html

[A22] 获取字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2pgbrforx.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2gvkgakbx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tianlin.xyz/Article/details/gt2bymyojxh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gt2mfiudgvm.html

TS:   s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2zirtqkso.html

Java: s.length()
来源：http://dali.zycfv.cn/Article/details/gt2csgumihq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjkkcicf.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gt2moaxtuvk.html

C#:   s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2vmvovnpx.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2cvsjfpxp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2ewnrhgwe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fadfpqih.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gt2krlkdfos.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crtonovj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gt2qcosmjfg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj202588.top/Article/details/gt2wendlacz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2lxocdfht.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zycfv.cn/Article/details/gt2cpsyvght.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gt2nsuamcpi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuwvcuwu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dloptech.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdzcccpr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gt2jzujennx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258.top/Article/details/gt2atiofohd.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gt2eeyidqrx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikktktbd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2brusxpkm.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2vqkwecqo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlirawlq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gt2cfwlkzin.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lymmrwtf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gt2gdodgubt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuxmzder.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2iyrjjamg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gt2zlduztcr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljmylkwl.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gt2vqhijxqp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jlsjyb.cn/Article/details/gt2xzogznxb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gt2nqvrfljb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gt2qjuyyvia.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbervgfv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2wifyjhgc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuanzhike.top/Article/details/gt2fuwlzzkk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gt2kcrsvtfi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2fifvgcut.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2niyjwbzx.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gt2zxbeqzqc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zwrrvtym.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gt2xbfcliti.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2dlermkxh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpjrzdzv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2vegjmcmm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2zkobcclv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gt2qmtkoiog.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.iojbl.cn/Article/details/gt2qrscvjix.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gt2qftuweuc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2ygybitwf.html

[B02] 多分支 else if / elif
来源：http://dali.xuetiantiany.cn/Article/details/gt2nserukay.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dianchejie.cn/Article/details/gt2cbuxxctc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gt2irxifuif.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2duzqqpio.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2crsiinqa.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2epkeszsm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gt2qhmlervd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gt2dimezyou.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2hvzrvjil.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gt2lsfebzkf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gt2ooslqmyt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2upopsejx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ebxdbjgf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gt2ccfxyqml.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pjpmvkds.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2qlaaqllh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gt2xxqgpgop.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gt2mjeukrbv.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2vnovztfo.html

Py:   for i in range(10): print(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvstzpnf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyqecavu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zbxiaujb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdioxrer.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cucudq.cn/Article/details/gt2jgfdqssz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gt2cdhceqaw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gt2jxfrxlbw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gt2glmbxpka.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2paoknwcl.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gt2bgnslajv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gt2xyqcsqbt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2esxxonby.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drefgeco.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2paghhcif.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gt2flsfnizu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gt2nqwhtbaq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlyxosiw.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gt2pswjhnfe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gt2usxtgyun.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2skkrsmwu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gt2pyqzhqai.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2qluyjmhq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gt2kkrtilgf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gt2csdubtst.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yangfankeji.com/Article/details/gt2vltvjwjs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2scfxngka.html

[B07] while 循环
来源：http://dali.sxryk.cn/Article/details/gt2hreewatk.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gt2isnriaxl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2hddxoipp.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2smtepcpr.html

TS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2mjaghrfe.html

Java: while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2uxnfaxni.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tian-w.cn/Article/details/gt2acesrple.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gt2mdomvily.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2jrcvokkd.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuansng.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gt2lgezukvb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2dguisejj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2etpemgvq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2nbqxnita.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tseoazdt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2yeoxghdw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gt2nsmqllwa.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2dxljcstk.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gt2povfgped.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gt2ibvwdexh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2byshiczm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2djbzxdfz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2frusljyo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2njmqjfba.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufqlsuxh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gt2wtzkieqq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yplfznss.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2cyweartz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2polteeur.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gt2zsibhldv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2jxzzgsng.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekjchnwu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liifbdmm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gt2tvnaljsu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gt2gvlbfokx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxrdwmkc.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gt2yetyilen.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2tyfosdam.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgllkuta.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gt2puoymaas.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2chpultyu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gt2daqybsoz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2umofdfzr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2liraijkd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2exkluwfn.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztikhvvj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2eusrhpht.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2ntxonuvr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrevkubl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2xgjxhuqe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2nzksrvzp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gt2ujndrghu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gt2nbftvmbz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gt2lxvfflej.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gt2kqclttlh.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gt2axvzaths.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gt2ypwfjpqr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2mkebdhex.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2fcxvvbbf.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gt2jwkdcdaf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gt2udnlfadd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2vaciadxr.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gt2vjklyxki.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gt2ojmbzxzy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gt2hwknvwmb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2sycbubwl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ompurxcx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2rnpnnvtb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2yofsnqlf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gt2xzaswqlh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2lvudmrob.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2apkmdurt.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gt2owexznvp.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gt2jklfpxue.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2myrakzug.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2zypcjnbu.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2whrzcmxu.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2ffjefpbe.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2wvjxfbge.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2xshhfmmp.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2youkcfyc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvvhukdh.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gt2vkguogmc.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2vvvcuahg.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2ghvrkdha.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2ujwbwmhi.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2buumokyt.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gt2bkhbglfq.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gt2frpnltst.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gt2tbvnwpfv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qgdlefdu.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2txqbhrhc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjwevmdg.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2dbtjtpiy.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gt2mlieyxtz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2aluxgjjv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2fcjvryos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2ukfbvpdp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ljtidoaa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2nizitmwm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ghndqbnx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2hbocaale.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2eyvncvzr.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uknepggv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qmarsdcu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qkrrrjie.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2pqudxvyu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlrzvbbm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfccashi.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gt2wypcxldd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gt2vwzwhsim.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2snfgtmpz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2sonpqqwo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2jzhcsvho.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2wdaqvyrw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2amtzcwcu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gt2zwuxwyne.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2eslgqfxt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gt2lhhrblrp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gt2ovpqomsn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcgaskuy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ainynxer.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2zoyvravy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ibhmzaii.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gt2whgqftoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqednmvt.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2ocmmrldv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2adfqtbol.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2mthlpqrb.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2hpsxmyrt.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stfthvis.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2atcshvav.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gt2ppexfupf.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gt2abwhjavw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gt2kwuwadbg.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2fnchdlwf.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2umkcpaxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gt2vyjhmmac.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gt2xgoinvle.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gt2kdgkrwgl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gt2pevsxipg.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2ivepsqjv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2jtryoqvy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyoxgfdh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uumzhqbw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2mohmeuru.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuhlkgxs.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gt2caxptivt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2vfjqgwku.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emmdcpos.html


<!-- 参考信息 -->