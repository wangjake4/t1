代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenlongwang.top/Article/details/gt2abugfujw.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gt2nmwpmfye.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqwspsfo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gt2phnkwuhn.html

Py:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhabcmma.html

PHP:  "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2kvxbqpgn.html

JS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2ngjiwvti.html

TS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2qpltyloz.html

Java: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2lcxqtkii.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2iniofonx.html

Ruby: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2xsrpmdgk.html

C#:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2uedyfyhc.html

[A14] 注释写法
来源：http://dali.pengpengdd.cyou/Article/details/gt2abgxhmgj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuetiantiany.cn/Article/details/gt2jptdwhlo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gt2jygqwapq.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2nduijxxk.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2ktrdadpa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhixingplan.top/Article/details/gt2nauopphz.html

Go:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2jggwgbxs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cdnleiting.top/Article/details/gt2kgvisoko.html

C#:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2swhdszjh.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2advweqsy.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gt2khmoprlr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2adpigule.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2vumxkair.html

TS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gt2upqeymke.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuanzhike.top/Article/details/gt2mxgbuwib.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xylfe.cn/Article/details/gt2fnzkpmwi.html

Ruby: value = data || "默认值"
来源：http://dali.9152youxi.cn/Article/details/gt2faonbcuq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gt2ryxhzcdo.html

[A16] 真假值判断规则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcorjzwf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2wbuakheo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhongyouzk.top/Article/details/gt2fejzlhsu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gt2xyvtljww.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jiqqbjws.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aizwys.cn/Article/details/gt2jokxfqsz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj202588.top/Article/details/gt2cefgcyha.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyilouyi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gt2nuwcwxnr.html

[A17] 位运算
来源：http://dali.gzhubu.top/Article/details/gt2znpmayex.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2yqlbpcau.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2ecsgptrs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2mynthrgb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2cgnzpbjb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2tjjehwwy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2xdukgpfq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2snmcrklh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2rausaugm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxinkj.top/Article/details/gt2fqycelsm.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2fjbwvmsc.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgdtghph.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gt2dwicpnox.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gt2zzgsqlbg.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigufen.top/Article/details/gt2ntojtnrf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gt2fccdyvvi.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gt2mggeuzcm.html

C#:   (int)'A'; (char)65
来源：http://dali.hnqzz.top/Article/details/gt2svjhjews.html

[A19] 交换两个变量
来源：http://dali.hysaishi.cn/Article/details/gt2gtfhctqz.html

Py:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2ypzvwgmr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gt2dfkqjqov.html

JS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gt2aglqmmiu.html

TS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebnzjhru.html

Java: int t = a; a = b; b = t;
来源：http://dali.yongpay.top/Article/details/gt2jkxgnmst.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gt2bsuqksck.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gt2jcbjqras.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gt2furpfqud.html

[A20] 读取标准输入
来源：http://dali.sysykeji.top/Article/details/gt2kdjkfjjm.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gt2csyjwnxr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gt2taruzlte.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aibaodan.cn/Article/details/gt2lnlvusre.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2ftomkgpz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gt2fjfscnpq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenjidiqi.icu/Article/details/gt2akuagaod.html

Ruby: gets.chomp
来源：http://dali.mhx1999.top/Article/details/gt2irqlfera.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gt2fvcdqmnc.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gt2mcowwzif.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gt2icgmbxhf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2wdhmbidm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2dhzoprsa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2vzibucgw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2enpqzthj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gt2ibbsyzmc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2fhphvama.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gt2jphqrxms.html

[A22] 获取字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2oifrzgah.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gt2ulmjyshs.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gt2pyzaqtvk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gt2xuvfxcrx.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gt2znrsogcv.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2dwitptkl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gzhubu.top/Article/details/gt2eymwalnh.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2dhrsybjq.html

C#:   s.Length
来源：http://dali.smart0.xyz/Article/details/gt2nqhctqyi.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdfvspoh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tanke756.top/Article/details/gt2egxyjkyd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2llxduukd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gt2ecfwzbxw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gt2sqbbdain.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gt2nloiponq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258.top/Article/details/gt2kncrpybm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2yokljrsi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouxotlqr.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gt2boulxzqf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.havefunace.top/Article/details/gt2ilggbxiy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gt2dsekgtil.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gt2hqqdqokb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gt2nftaxfra.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gt2dqpfjvap.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gt2gtejltjp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cqqwz.cn/Article/details/gt2aooauipq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlblqnjd.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2edjriyjh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2rqtnqent.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2zrgaazax.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbqpipob.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gt2danvjyhw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sxryk.cn/Article/details/gt2gibfsgfq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gt2yrtatbko.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gt2nusisyjz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hleuyecn.html

[A26] 类型转换总览
来源：http://dali.jinqigfzy.top/Article/details/gt2erlhyyaz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gt2avxrwhhs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gt2excgnjxl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gt2nbbxzzww.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2octbpvit.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gt2nglxlawy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gt2vuhkpwet.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gt2spukcchl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2jirucret.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ioqzyddg.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gt2ejthujmv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ypvvwnef.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gt2zumovgxj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gt2kxqulnxy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gt2xnhpxkph.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afsrxwux.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2veeilstv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2xgyifxtu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gt2hianxupu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gt2vszsitqi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2kjdtzrnn.html

[B02] 多分支 else if / elif
来源：http://dali.xylfe.cn/Article/details/gt2fwezurqg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyxzggwx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gt2lidlmbtn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gt2svoyqzgo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2phcabnhv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gt2wxdlyrye.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvjugrvv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gt2asptazmv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2oolfvynn.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gt2suzucben.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2nhvvfnco.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blyikjqy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2uwtistvf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzlnsxwv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rclzrvvy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gt2jqrbnbbn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gt2qbndekuh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gt2oudmskps.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2mspyopca.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2afoikcnc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkxpqnuo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2jtgrvgbo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2lugdrpbo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rmhfbjxt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gt2nlkixefb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj202588.top/Article/details/gt2lsmcqsda.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gt2umceakce.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2etlpgnej.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gt2ryvmbgeq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bvasosch.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2seidspbq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2uvffrwao.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2gokwyamh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.haohaochexian.top/Article/details/gt2xmwyrpqh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2vtdjgegs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gt2cwslansy.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gt2lsarqjdd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gt2panbqyau.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gt2cuvlvumk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2ovvvsioh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2vkqxwisa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjdymfo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gt2qiycihdr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gt2wzqxewnm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlqpjewy.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gt2edxktcgp.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gt2bojncvvv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gt2xnmsvdaz.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2pdqrxkix.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2gejltszw.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2msznkcto.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gt2lttsuyhn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gt2okxogbrm.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xaigngym.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2bdppdaiv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gt2ryoqlzfg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmfhjamp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2vpwrrckv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2knlhktab.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idcllgrx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2rzvnjrat.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gt2cuteauwd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvwbnhlt.html

[B09] break 与 continue
来源：http://dali.9152youxi.cn/Article/details/gt2qlczmzqp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2gledbmtx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2oznlbggy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2aolhdmjq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2cnazbmwv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2msihznop.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysniyawu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xllryfnt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2muffgvaz.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2rysxbuau.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gt2jiagermf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ghaqjdro.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddzmkfuv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kheqyccf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gt2ongeilbm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gt2euzvuwxv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wudzdqyv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gt2sjqqrkur.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gt2ihjchvzc.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gt2jcdyqppt.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2otqvnebm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2jazqkqzh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2vjeywzsa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2hftraeso.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ynswosvy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2iexfwevr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmebqwos.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tahmippc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2scirbrli.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gt2jhmrqehh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2oxhulvsu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijkdajni.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2bjsuehrj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vtgkycda.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gt2ptivvfob.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258.top/Article/details/gt2jvhaikvp.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gt2wcynsekx.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaqtfpaj.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ctblwffs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2tsorgkxd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2yqkafrfi.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gt2nokabfhh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gt2wctximmc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gt2djqssfyr.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2bwnnurls.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2kgbyafjp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gt2edyrfxlw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gt2pclbcwea.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drwxhung.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2hqnzprne.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipmxqrwt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2rfjxyple.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2ijqeqoll.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2zkmwmptf.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbhepxbj.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gt2eozfanox.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2onipronu.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2zjfomtcf.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2lswqczjv.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2nwzfizcj.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2etzqotod.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2lozdqwbg.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlmtbpeq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gt2kixljlmj.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gt2ctkbwcxt.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2hvvjwsdn.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gt2wdwhwgmt.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gt2zohcziiu.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gt2brlppglm.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gt2jmeloofi.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2mhqsrpxq.html

C#:   if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gt2yjyfbddm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yogbtdfe.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gt2lqpulbgp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2raxuuspb.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2syeqikwt.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gt2eurdlwwj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2umloznvh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ibnratlx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2pcaqwfty.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wftmlssl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmxgdury.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkhxtjyr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2gtnriayf.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gt2foxwpdgf.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2adgxcxlc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2arniomcy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2ytctvprm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ccthcvwg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gt2kjndjfoa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gt2albpzhkv.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gt2laooevux.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjsjzktc.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2zfozyuxk.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gt2dzdssanr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gt2opwchtvj.html


<!-- 参考信息 -->