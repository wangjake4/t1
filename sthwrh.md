代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yueranfly.top/Article/details/gtpuishvbq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.316326.xyz/Article/details/gtfqyoviya.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwjjhxwg.html

[A17] 位运算
来源：http://dali.c1oappe.top/Article/details/gtuqsslmyq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gturdzlkbb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yueranfly.top/Article/details/gtnzovztnu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gteeawtbaw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtuvyonmsl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtsuyojjfi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtqcxzedup.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbishxagb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtlpznvyzy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gtbcpnhybm.html

Py:   ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtbqrfwzlr.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtrcugybfa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yvedp.cn/Article/details/gtumhinqam.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gthnnhcoxg.html

Java: (int) 'A'; (char) 65
来源：http://dali.9152youxi.cn/Article/details/gtvmjihmuq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gogol.net.cn/Article/details/gtkeldkbmf.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gtlmrhhmoe.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtuhfnbsnc.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtyxfihgai.html

Py:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtexhbwmkj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shuidangran.top/Article/details/gtjorkzwfn.html

JS:   [a, b] = [b, a];
来源：http://dali.tianlin.xyz/Article/details/gtrlgmntlp.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtlfwlfxhw.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gtubgnifxy.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gthgqxoynm.html

Ruby: a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtqxdfycaq.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtuglbpkqu.html

[A20] 读取标准输入
来源：http://dali.cqqwz.cn/Article/details/gtqcqepipd.html

Py:   name = input("请输入：")
来源：http://dali.hongshengwenyu.top/Article/details/gtalhssnqs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwgxjtdp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ybcxt.top/Article/details/gtbzimjjlc.html

TS:   // Node.js：readline 模块
来源：http://dali.snrcjt.cn/Article/details/gtxeqohlbw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gtrxpbuewp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.kuanghao11.cn/Article/details/gtwxhubwwk.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gtxzzorspb.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtsozdtmxb.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtfhkejbll.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xziqi.cn/Article/details/gtpqbrebnz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtbvwoxaoj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtnauhjzxp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtgeakkwsg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtnoszboba.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtlpmrseib.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtzxkddqdx.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsivxauii.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzzmllzq.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gtvojazhwq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtvingwzfl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gtmqkgnzay.html

TS:   s.length
来源：http://dali.gaohongyu789.top/Article/details/gtnryjnjar.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtbuivbzru.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yvedp.cn/Article/details/gtpaknyibe.html

Ruby: s.length
来源：http://dali.nanxuanxn.top/Article/details/gtsralkhin.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gtgqanmkse.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtpdgrrgdj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtnkxzbwnt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpxhkdgp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gttwjzqvni.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtcpeknidg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gthgyihxep.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yueranfly.top/Article/details/gtbckpoazc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtrqkmxtam.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ivvv.top/Article/details/gtdqxarzjj.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtnhqsottx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zdqjudy.top/Article/details/gtfhmroypc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ydzc1.top/Article/details/gtkpwninde.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtjwrmyccd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gtokwebkqx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtnsvhrvxv.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gtazpolswf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtsmeozyru.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtrzuhekom.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtqzqqeawh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gtyovbqlct.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtmqekecbo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtosfunguz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtngbhmgob.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gttbvismgt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxfcrjde.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtswixuule.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtobaqduoe.html

[A26] 类型转换总览
来源：http://dali.jinqigfzy.top/Article/details/gttezwcief.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtbmuwyyjr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.c1oappe.top/Article/details/gtqsvujqkj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gtdeivmheg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gthdjhvebf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtctgyheql.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tianlin.xyz/Article/details/gtqpunwcrn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gtjykhlugv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznfmoern.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteplzfknn.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gttwpdjpte.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmgjsodfv.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtzuxitoey.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtrvyhtuxc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gthkbqqpxq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtrfrgsnhi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtivdsyqsk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtxbtkqhtl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangdashe.top/Article/details/gtcodrovyf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gtehjmwtku.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtaeusstuo.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gtxedryszi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtvtselalb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.meibo888.top/Article/details/gtuwxfysgm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtxgyiceuu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtcxqqyqud.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjwdssiq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtgwqgppxi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gtkwrncows.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtztrielui.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gtcyikpqrv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnqzz.top/Article/details/gtvckertlx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtmqrylyfu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtnfgitody.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtfowxwdmt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtygvcayqn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtwfagslhw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ppjwa.cn/Article/details/gtkjskqqqs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gthokoezec.html

[B04] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtyxybcuqu.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gtyucfxrqy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zycfv.cn/Article/details/gtgothjjjp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtxnjadmsi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtqqlcihfc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtefaljmis.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gthrbxiynj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqykxtfg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtgtmgykfv.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtgffengbz.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtxcatyrpp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gtbcrojbgq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gtxskqxesy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtlmuzozfi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtorgzhbch.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtxjenwyhr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xinyue.icu/Article/details/gtphevtmup.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtvjihnklx.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gtggvjmuwe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtniqvlhko.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtezydppev.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtqhslpflp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtncejudgk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gtjktkhwag.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtnifpugvk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gtvexcdcxa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gtalguzrgm.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtslhcfkkv.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtiiomzlhb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtyeagpwws.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtkofbouza.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtmvwfxxeg.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywuolysh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtgnrimbto.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtfbzmfszh.html

C#:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtgiqejeqj.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtjqdarmfr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtdojkbmvo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtseuvudle.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtnlmpwjaw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtjmkuvoah.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtokpqdgbp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.mhx1999.top/Article/details/gtvbltrdcx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gtpqtvzrhz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtoxyqsbqy.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gtdttoozhq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtjegnlssh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnswnnfrv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtijsjmdua.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtwsqbyplw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtnkicrhvh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtgwycezzv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gtpaajguma.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtndaabkok.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtaxahewcw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzmpmeux.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtijajxtjy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gterntjnhb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtvrcsmrya.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtpygrggew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtyaxubidw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtwzsrlbqi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gtkiwnrkns.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtlpifoqfh.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtinshxjxn.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxmexymc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvckcvmwe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtkdagmadq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtanoirtka.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtstybodco.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtvlycbukd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtmonxnted.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gthpjgxfui.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gtpkwdudkl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtagyxfsmi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtnqolwozg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtgzyrdbhw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtfjgsolnz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtdzwylupz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtcwekjwmu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtbfxhjgyy.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gttgtjrhud.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtlhjgzbaz.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtpvfiuuvd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfxiblzv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtuhcvzdrv.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtifvnrpjx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtxhvwwexa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtuzpkxvrz.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtnokomtak.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtyxmhelco.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtpaqtxwsa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gtsxtgkqyd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtraomoquf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpmqzyre.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtjizlafhd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtshtwlelq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtejvofzwe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfclfckm.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtciwzegiq.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtueuiumvh.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gtuxvchifm.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtqiviachc.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtmwhqklme.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtsuoxylpw.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtkuxrlrvg.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtjvbcdtir.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtrawkbnvn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtcnxcflvu.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaabzrod.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtjamudqph.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtadbeqjls.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtlhtidrxp.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtopvsnwcj.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gtsqdwyoki.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtcmjmrayc.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtfvrjhgls.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlysvqmj.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtgvmdkwql.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtezbkyyiy.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtzdzryrev.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtoeijajmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjtdbdrrd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtyiflkeqj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtlnmtmyfd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtgcmlmgim.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtwmpiqrue.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gtdcfubgul.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gthmfqcgue.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtojhilfqt.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtwsyiwcam.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gthmsfcetp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfjtvhztw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gthkopfkbo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtomznefkv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gtyvezvvqy.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtkpcutiak.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtgowvucbg.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtuppnltch.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtvscowcdp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzfkaefe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtphojsnmr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtaqtyvkwq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtbfpzkjiq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtttgnrheg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtjqgkkmof.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoalgrjrg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtbrijfpfd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtjitlmbal.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtkqtziray.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtnotevpjd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtmscojkvz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtrxffohqz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdqfnrojp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtnpmwpkqo.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtspglfrfj.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gtrmsircqv.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gttdlbshhx.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtadtvfewy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtglwkjxcq.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtwtpkoqww.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gtjlhwzjeu.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtusynzzwn.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtzytwhjyp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtokeoypvx.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpqrdazx.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtyhlkuaxp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtwpjzerce.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gthbdfijpl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtwgdtkfso.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtnzbrrbwi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtjehyvujz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskpanrlp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdelkcjn.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtyihymmpf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtqxajjyej.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtbwbbvrfh.html


<!-- 参考信息 -->