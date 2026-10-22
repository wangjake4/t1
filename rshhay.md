代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2wfwhmjxl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2pzshfeqf.html

[A12] 字符串插值 / 格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnkmpqfu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcfnohkw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxinkj.top/Article/details/gt2acbwzodw.html

JS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gt2bcdmlthm.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gt2fkumeyyp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yongpay.top/Article/details/gt2yuzbwuyz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bndjormj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qubkymcg.html

C#:   $"Hello, {name}!"
来源：http://dali.xinyue.icu/Article/details/gt2ciebetqc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhoulong.xyz/Article/details/gt2ldhimmtl.html

Py:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2qcrvewok.html

PHP:  "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vduuvuty.html

JS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2vusgzjpw.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2xdwifiru.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2hzbevmyg.html

Go:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2edgkuosi.html

Ruby: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2uehujwnt.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2kafuwnni.html

[A14] 注释写法
来源：http://dali.haohaochexian.top/Article/details/gt2risejbfx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cdnleiting.top/Article/details/gt2uqrepkjy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2ejafpbgb.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2llcwpfiv.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2cgaekkvs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmhvxpwl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2yxlychmn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.havefunace.top/Article/details/gt2cylbzmgn.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gt2xprzoavv.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gt2wlctvwtb.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2hzzxxinf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gt2ecpijxfo.html

JS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gopdjtvh.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2vpqghzxh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdmvjkna.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gt2drkjfbvb.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yshbbmao.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thuwwlgm.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gt2vbeskvpe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2xpcdequc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gt2xqcyghez.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gt2lvalgfqy.html

TS:   if (!x) {}
来源：http://dali.gzhubu.top/Article/details/gt2rpmjaewl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wvpxkayu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruklzuxy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnxiangtu.top/Article/details/gt2zoeditjz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2erclnyek.html

[A17] 位运算
来源：http://dali.9152youxi.cn/Article/details/gt2mujlufep.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2zzfzteio.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2dpehsumz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2gqmwaznx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2ruulkwpl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2bmfsnqpf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2vpfsdmam.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gt2bbgpdomf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2oodpbvla.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gt2dkocfiha.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gt2taneekaq.html

PHP:  ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gt2tkxuojyo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gt2yxmyqsxf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gt2mlkwdznh.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gt2ogdoggws.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gaohongyu789.top/Article/details/gt2kkheuymt.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gt2fimcyanr.html

C#:   (int)'A'; (char)65
来源：http://dali.ydzc1.top/Article/details/gt2kgnefuum.html

[A19] 交换两个变量
来源：http://dali.hywenlv.cn/Article/details/gt2trdzbfcj.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2qdivxrxi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gt2jyfpqcgq.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gt2eocejouz.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gt2ahkpdkkk.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gt2xqpfkamo.html

Go:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2jchnvvxh.html

Ruby: a, b = b, a
来源：http://dali.sweek.top/Article/details/gt2iwbrwrcu.html

C#:   (a, b) = (b, a);
来源：http://dali.quarkkingdee.top/Article/details/gt2bhitlmdx.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgqvlgca.html

Py:   name = input("请输入：")
来源：http://dali.gzhubu.top/Article/details/gt2ntvgqggh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gt2yldohvbm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tianlin.xyz/Article/details/gt2osfwahqw.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edmzifzj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gt2iwvnoujy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gt2qbthvuip.html

Ruby: gets.chomp
来源：http://dali.aibaodan.cn/Article/details/gt2imaynsot.html

C#:   Console.ReadLine();
来源：http://dali.shuidangran.top/Article/details/gt2vzknqnjx.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gt2praialbs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cashguo.top/Article/details/gt2skjmqkej.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2mpnomqvd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2nzeyvjgc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2paqisqxx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2kvhxnrjm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gt2cqallbxa.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2soponmqm.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gt2hfnabyzm.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gt2dntiprps.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2eecibfks.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gt2swsdpqui.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gt2akhwjdss.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gt2aeijqneo.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gt2bvubfkbw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xritfkfk.html

Ruby: s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agtnpmep.html

C#:   s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2naproiyy.html

[A23] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2crfzwhji.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2pdmslrvr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.bjfxy.top/Article/details/gt2eyogebyw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2zaelszmo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gt2vuhxcmqs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2aftnkiga.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnqzz.top/Article/details/gt2wvrfovre.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2ayamvhjh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gt2rtslzwvb.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gt2ltblomuw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gt2qqwdplbu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gt2wxlretpm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gt2fjxmeqra.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2auiemgue.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gt2avkqljdi.html

Go:   strings.TrimSpace(s)
来源：http://dali.daria6918.cn/Article/details/gt2bgrttzcf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gt2mkjeufpj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gt2natmjtzw.html

[A25] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvigobgs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.snrcjt.cn/Article/details/gt2bemlxswt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gt2ytkfnszr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gt2jzdjuejr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gt2ykyfmiaq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2xzhfftfu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2kekmhvay.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gt2oqcuuwph.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gt2ygnewicg.html

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gt2avgnxmhw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixrrewhp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjitahfh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gt2zrjifixm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gt2beaahzly.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gt2bqkjreiz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gt2jibwwjku.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gt2likcwrke.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gt2mjmgjcwc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jbxfgqqu.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gt2reikaebu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ovhmegyk.html

[B01] 条件判断 if / else
来源：http://dali.sxryk.cn/Article/details/gt2ljktfxnx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgfzy.top/Article/details/gt2mbfezytf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gt2mvwxfthc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ythuakde.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2ksapccsu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2yflumchj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenlongwang.top/Article/details/gt2jxwgjfmu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnqzz.top/Article/details/gt2xzxsakrn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2emwxjfnv.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gt2yskoulfk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gt2jddyoxxr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfdmlgi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2riwmidsc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2mwfsvamh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2bnmbmoxg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gt2dilszfbb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gt2kvxnfdqz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2lemygsxp.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gt2cypnenan.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yonumen.top/Article/details/gt2hsffrtbj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2myrvayuu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2clyzfcuc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2xbgpotbd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2afpybcob.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dunksmrx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueqpssji.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2daqlckis.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gt2vsdritqe.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzhwxwzh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zycfv.cn/Article/details/gt2kjqooult.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gt2rxcdpjot.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2suuzhsxx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gt2utxizrei.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gt2scubozwd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aizwys.cn/Article/details/gt2bvvxrmzf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2bofmqitl.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2hwoxywfg.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gt2aaismkik.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gt2suriwnpv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gt2snmoozjv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiahebsw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gt2sxbjzizq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gt2mjcrutwy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gt2azzymbgd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gt2uvmddxmi.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsqvrmvw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gt2ecoywvmd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gt2bvcjhvrj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gt2xczsgsyk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tpzjhtxr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jofmbfdu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gt2kzgvrkpt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2qmpiwdkz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wgvskxkc.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gt2uvwhzgfv.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gt2nzdgwhzw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2ebibzzco.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mhscopvo.html

TS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlmyequn.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2neaxkirm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gt2sfggmbvw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gt2sfnobovs.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2dzfczdff.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gt2ghuvhauz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gt2vdynwbiv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2pqdwdran.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2aouabwme.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2bpkgufde.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2skbnzdwx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gt2ibesgiqo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhovcvnx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjrcgwfe.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gt2uguadyrs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhtvtxzm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozntpwec.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dyodcaop.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2corrawfz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2cyyogmss.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2judcllnr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gt2iknixujo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2wiupqxyx.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdgubkei.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gt2yylpctmu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2criftisz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2lckdyynk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2vcqvmayf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nolsnfqx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2frugejvg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2zljjupzl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ydwyagvi.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gt2lmktmtev.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gt2ogzojppg.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2rbhginbh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxmcphzt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2ymgcbrfn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xysrezeh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2igkubfij.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqemphsz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2nxvfrlno.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqfoqsqw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gt2ujlnmomy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2gmhiztjf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2qpunkpcs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2nxeyfaus.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2oquydgiz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gt2duxurhgj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gt2xxozbkgl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2avpvdxht.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2osfjhwyy.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gt2tdrqxvvi.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gt2rmyethrd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ywxhdjng.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gt2soayncmk.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gt2xdthumns.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2rmrpudaj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gt2ftdljsoh.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gt2uhwmjiig.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gt2iswbwzcx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gt2pxwgpery.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2scpkguou.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tctgsdwc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhvqjli.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rchhmutq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2meiupjfp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2depdvbaz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2vquwpcgx.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gt2ikadjysb.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2iskizrzq.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gt2qticzqcm.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2qbqcctlg.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2nhfalphu.html

Java: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2akznnsqp.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2dzcywlxf.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2pwkymbro.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2agefaabr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gt2nkzaabea.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gt2sgwacbav.html

PHP:  if (!$data) { return; }
来源：http://dali.cashguo.top/Article/details/gt2eyxymhvv.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2xnocxfti.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2qwefrfdd.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2zvzxlpjf.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2yolthayx.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2qgedclhc.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2dkhzhtpt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xgvftnpq.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gt2fxqsgdgn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ouqxvanx.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2jtcwokaw.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gt2zankftrq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2ptvigzxc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2ffgxsooi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2nvaheqbq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2ksxypmzk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gt2exnhkmdm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gt2ojslgvuk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2rxntljlh.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2qfmvnyap.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2qpjkfsxg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gt2thsaxrxh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2fjsavzqt.html


<!-- 参考信息 -->