代发 wailian999

[A14] 注释写法
来源：http://dali.zhengqikj.top/Article/details/gt2nzgumdim.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anpmmfqk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gt2kvlbdenr.html

JS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2omoxmeyf.html

TS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgxvqsks.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slaeswwv.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2ilmesvmi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xctzkekt.html

C#:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2emdsbcza.html

[A15] 空值判断与默认值
来源：http://dali.andypj.xyz/Article/details/gt2lqjxkutn.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gt2mpaadsna.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gt2bxdoghbs.html

JS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2lycxowbo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2otsviykd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.havefunace.top/Article/details/gt2kwvtpmdo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gt2bwjqavia.html

Ruby: value = data || "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfslzrgl.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gt2tqfxmbuo.html

[A16] 真假值判断规则
来源：http://dali.sufxvd.cn/Article/details/gt2nawgyipt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gt2arakubjn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258888.top/Article/details/gt2iilxjjsg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gt2wommddbc.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gt2rfigwdgi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olchbbdq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hfpthk.cn/Article/details/gt2eribofaw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2paxcwsal.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2aegpqqyi.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gt2xyeibzhj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2tpdkskef.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2latqaxyv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwvlxiuy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2znsdomsj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2bmhgzdbt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2acjskrhf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2lnyyqrex.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2alaaissv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gt2otvhymtg.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gt2jddwscts.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2dnlpcetn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2socayhdm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gt2dcnvdbwm.html

Java: (int) 'A'; (char) 65
来源：http://dali.haohaochexian.top/Article/details/gt2csfddbbx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gt2mtqglqgj.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gt2admtgvag.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnrqivbb.html

[A19] 交换两个变量
来源：http://dali.yj202588.top/Article/details/gt2vaflldjj.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2awzsewmu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nwbrower.top/Article/details/gt2mhhejrdj.html

JS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gt2usolahxo.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsrapsqo.html

Java: int t = a; a = b; b = t;
来源：http://dali.yanxiufei.cn/Article/details/gt2dzzcljkc.html

Go:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gt2dcvoewnz.html

Ruby: a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gt2tywtcwdg.html

C#:   (a, b) = (b, a);
来源：http://dali.sufxvd.cn/Article/details/gt2itzlwzce.html

[A20] 读取标准输入
来源：http://dali.hammf.cn/Article/details/gt2zqgxloxw.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gt2engawcpu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wasozyzu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjcayero.html

TS:   // Node.js：readline 模块
来源：http://dali.jyoumei.cn/Article/details/gt2xpeuhkxy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gt2viptweek.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.pycfn.com/Article/details/gt2tmlqepzp.html

Ruby: gets.chomp
来源：http://dali.fengsongda.top/Article/details/gt2abkfublk.html

C#:   Console.ReadLine();
来源：http://dali.zhiwuduotai.top/Article/details/gt2urwrwmzx.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gt2xqrgxzmg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangdashe.top/Article/details/gt2vsbccrbu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2htfdjgcy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2aalevwhd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2zhxbomgq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2rxoeucof.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2yxwqsyrf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2cjcetxvq.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gt2wvjbwxdq.html

[A22] 获取字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2dlipfepb.html

Py:   len(s)
来源：http://dali.yj20258.top/Article/details/gt2squnfutj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gt2scmrixuy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.snrcjt.cn/Article/details/gt2rnsaivtv.html

TS:   s.length
来源：http://dali.yj20258.top/Article/details/gt2njgcsurd.html

Java: s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkwsezdl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gt2dvxijvko.html

Ruby: s.length
来源：http://dali.tanke756.top/Article/details/gt2newqdyhi.html

C#:   s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2vdmczcfh.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2wsatkfmq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tian-w.cn/Article/details/gt2npctjkud.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2enthfwju.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2ztzulufy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2fainzfqf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gt2esjecqyl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gryixorg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2agsklyni.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gt2wrvtavaz.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gt2alxtejtc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gt2cnebfwkr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gt2ctwxroot.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gt2zmofebxv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2qsgdbulb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gt2qyhvuykm.html

Go:   strings.TrimSpace(s)
来源：http://dali.316326.xyz/Article/details/gt2tihvxchm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.birdmap.top/Article/details/gt2qjgwuhhu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnqzz.top/Article/details/gt2ibpfcptx.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2wyejxayi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gt2htqxdxug.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangdashe.top/Article/details/gt2vkmgfevt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gt2tkfcbocr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gt2tottkxto.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2tendrphj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ueepywjj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gt2yhbyspui.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqnxuguk.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gt2wokmlvqb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjxkmthk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gt2pqjroojh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yanxiufei.cn/Article/details/gt2kaejsqps.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daxiang520.top/Article/details/gt2jybqpvde.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2bvirrkbh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yonumen.top/Article/details/gt2rzmydvey.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2jawnnryc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2wnrnvpap.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qadtebsv.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnflxuih.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2amhrdodz.html

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gt2kfasikyr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gt2mkugjoux.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfcvzomg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2yztwksbx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpktfpev.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2kqnhfbyl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhengqikj.top/Article/details/gt2lldcblty.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2hlgsbhop.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsfrmeip.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gt2sczfzgyg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gt2qokxpctq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cashguo.top/Article/details/gt2wydzkzyv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2yyzmaziz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2wwtqqkiq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2bkyqlrih.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gt2vnpemwgx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jelmjouc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2ofrrnwng.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gt2hpebznhy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gt2ovchjjcy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2rzwldphe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjzosgwt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xvklrojt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2seccmqpa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2bpqstngx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xinyue.icu/Article/details/gt2pyfrjadl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gt2uphfymru.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2jvbjuahc.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gt2nxsunhix.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2jthkzsow.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2ctowuvjb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilkehjfd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gt2nfgsmzgh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gt2bnrhkojp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gt2vrkchprp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2dsevyefq.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztjfuygi.html

Py:   for item in arr: print(item)
来源：http://dali.fengsongda.top/Article/details/gt2jloptqyc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gt2qvmqwprc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gt2bkgsngsk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2pjateert.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2nirkdrbq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gt2zausreha.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gt2oldjbeca.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysqscpfc.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gt2dgujsiss.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gt2pskyblwm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhxtnidt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynrspxnf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2ggjlmojv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.havefunace.top/Article/details/gt2jslbedyg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shuidangran.top/Article/details/gt2ooacxzvk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gt2rwytsfsd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2fccqfqay.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gt2tdbtgcho.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2iincynai.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2rkdcymyb.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2znvwtbed.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwklttbf.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2vebksjrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gt2rrwabtfx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gt2mxxdvofd.html

C#:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnuukvbz.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2dnguifvw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gt2uhcdaczh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vicpgwww.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2uhdmwdgu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2logakbtk.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2wvhenxzb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gt2syvnzrvk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gt2bmtipwhx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdzeugie.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlfgobzn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gt2facpwkyf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2dgfufkly.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vnzgojkh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2azzpzeht.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2pcpkzfyd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2jljniaze.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gt2zkmgzgal.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2amiadixh.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gt2huhparrg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gt2cbtmgnbd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cptjjzpp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2bcqpcihe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2jkacazvv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cumwmxyb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gt2opypfhtw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gt2denuvkua.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2ubdjqjfd.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gt2qmcdlugf.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gt2smmckjki.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2qsdblmfe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2wdzruuvc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2rvtnpvpo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2brikrhcl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gt2qvcwtohs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2prcvfmct.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gt2jrffbdwa.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gt2kqvaqzsh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxjljxyt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqxlnbrv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2dsubvesn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuawolv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2renlqbeb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gt2kornspsc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2peoiaojx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gt2aqibyesh.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2nytwskdy.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gt2zpcqiqss.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2ylhutind.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fikezrem.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ptobwclc.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gt2kwygwpxd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gt2feakxgvr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gt2zgoqxyjj.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2nirdxcqw.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvocnndh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gt2vapdapvs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwehzkeu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2natbdtcy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2kczedbiz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ofhjfpqi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gt2cqtfriwe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2nlvulmmu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2gebcsoke.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2esoaugzs.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gt2fbjlzsvj.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gt2expfasbt.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2gpcdiavm.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2ogldeita.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2iiztctul.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2odyaheho.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2lhdrvgqg.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2tevxbjjr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gt2smrtgith.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gt2smpnahzt.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2abfputgo.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2qraxlpac.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2paellgkd.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2zmcmxsmc.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoxtpobd.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gt2jadhbgqc.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2gwsjkriv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2omyxymjq.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gt2wbeqeleq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rkompyqe.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2uyhuizxh.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gt2asyusaoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2amfkuphk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ivuywhhu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2fhsuehbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2djpojquz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gt2jgzlzlma.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2uqgcailp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2ztpntspt.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2jkmnwgcx.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gt2unrvyoxg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2uifjuarp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2wyhihqcr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2pziocllh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2sctkdzay.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2eriwqyar.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gt2iwjvbagz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukifpmjp.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2kxnokveh.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2lyoqtdjv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gt2ntjuvrwr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2iprfimms.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2cggxfnjb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gt2owjbyhwn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gt2bxhjeaaf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gt2yuneaexx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2juclhcct.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhanxmge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2boascrdx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhwinkmc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2gcdroxvt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gt2ncmgjwdh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2hlyprfvb.html


<!-- 参考信息 -->