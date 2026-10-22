代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yueranfly.top/Article/details/gt2hfyloemt.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gt2eqgxixac.html

TS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gt2htwhcnoy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tianlin.xyz/Article/details/gt2xxzimtau.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.9152youxi.cn/Article/details/gt2vvsjrkpg.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj202588.top/Article/details/gt2abxbxjzf.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gt2pyqvakoo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xylfe.cn/Article/details/gt2dfygtbyc.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2omzdexku.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2yxfdaxpn.html

JS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2gddsuksx.html

TS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2ejztkhiu.html

Java: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2izpxbhjo.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2donzdkat.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2zkxvvblc.html

C#:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2dqlliidq.html

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcedjnad.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yueranfly.top/Article/details/gt2wrteulpj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2qsihhdxx.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvzevcgp.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2eqspayux.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yangfankeji.com/Article/details/gt2zozsyevk.html

Go:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2tqjoeeci.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258888.top/Article/details/gt2lntgjtlg.html

C#:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gt2axgayylw.html

[A15] 空值判断与默认值
来源：http://dali.daria6918.cn/Article/details/gt2hfodufca.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gt2szqgcvog.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gt2jmeyfqtd.html

JS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gt2fhrzqqxb.html

TS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gt2ldhltejh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nanxuanxn.top/Article/details/gt2cfornefi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpbugukq.html

Ruby: value = data || "默认值"
来源：http://dali.haohaochexian.top/Article/details/gt2gpabnnxw.html

C#:   var value = data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gt2odjvaxcl.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gt2tferoazm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gt2xtdbycxp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gt2dotbugka.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.quarkkingdee.top/Article/details/gt2aavzglag.html

TS:   if (!x) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ermdlhrf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2klobovpx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guannengcc.top/Article/details/gt2abjbegfx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fengsongda.top/Article/details/gt2snumlvaa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2czfxcoma.html

[A17] 位运算
来源：http://dali.dashuyun.cn/Article/details/gt2qflgyxso.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikqvcukq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2dhhotuxd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2fayhxunl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2jdktisdc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2mrecpnmx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2byffklit.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2xrqoaasf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2xpsgcyaj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj202588.top/Article/details/gt2nugdwyur.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2sfoijfqq.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gt2knrypdgd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gt2gzaurnoz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gt2hdahwqmu.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gt2lwomlrjc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yanxiufei.cn/Article/details/gt2cofvheyl.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gt2nckhhqle.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psnwdmee.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gt2cavnlkie.html

Py:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2ftfjbirh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gt2qwyddwhq.html

JS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gt2cyvapfrn.html

TS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gt2zbognhnt.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gt2vufllihz.html

Go:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2lddfxmat.html

Ruby: a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gt2msuqemvu.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gt2zfvmxdfn.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gt2bqilshdc.html

Py:   name = input("请输入：")
来源：http://dali.zhongyouzk.top/Article/details/gt2rrcfumtf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yvedp.cn/Article/details/gt2utuqwngv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.0kj1m.cn/Article/details/gt2vebomtlw.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gt2wnmtaifo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gt2aimnbvep.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.bjfxy.top/Article/details/gt2pkwjcuzk.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gt2uswzgqsd.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gt2hvsdznkv.html

[A21] 保留指定小数位输出
来源：http://dali.snrcjt.cn/Article/details/gt2qrufstdk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2behqtefi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2spwhbtom.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2dxmjecby.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gt2zxuhavlv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2elczmwxu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsphcehw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2tanghsvb.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gt2xwuvxqpp.html

[A22] 获取字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2mnmwnfwb.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gt2hvwioqsd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gt2fwzvgsli.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gt2kvzqbzfq.html

TS:   s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2rfvmbclj.html

Java: s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2ovhgguee.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ohhprcvx.html

Ruby: s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ataxpmco.html

C#:   s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2dxzmsfjo.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2kzvyvnkd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.bjfxy.top/Article/details/gt2yelveedo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gt2ikhzrmkb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gt2rvumfkuh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gt2uxkvoggp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2cbsvvgrx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj202588.top/Article/details/gt2nxrsyhmq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykztnonw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hfpthk.cn/Article/details/gt2wnjcelym.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gt2tspddkvn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zdqjudy.top/Article/details/gt2lbkborxl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fengsongda.top/Article/details/gt2vwywooae.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2fceieqax.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2ugjjukhd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gt2kjxzgjje.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gt2myjlzrbm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gt2xltsmyfp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrakxiym.html

[A25] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2wyumeggw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxuanxn.top/Article/details/gt2aohyqcwp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gt2wckyjmfq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2nqdvfgvi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gt2posskqyq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gt2blggxwil.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igcbujeg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gt2wstmympi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gt2nsbgwvkr.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gt2bjvnliow.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gt2rrqrzlzs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clexfpth.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.havefunace.top/Article/details/gt2kixzqxfc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gt2wgixcydp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gt2qhjaxpxy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gt2dxqxhwkn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aibaodan.cn/Article/details/gt2wufbymqr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gt2cbhsypxp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ynbiaguw.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gt2lrgnjhxy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2euzdfxch.html

[B01] 条件判断 if / else
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gddxeuiv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gt2gjxbogwo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aizwys.cn/Article/details/gt2vgzkqead.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2zfgvxjie.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2lzhuzqig.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gt2nwsxkzkn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gt2ldqbutmz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2foxjwwqx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gt2siwngoqr.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gt2nyqiorsy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gt2wejrucwc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gwuxltzt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2nwyejfvu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2klyupqsh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2hpevwtuq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwgyknwk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sysykeji.top/Article/details/gt2xwtceqvm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwbapomj.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdoyonrk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgukrxot.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2dpcqomtg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2nigguhoj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2mnvsiyaa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2nizqcinv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2ifttmpje.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gt2xtjpfqan.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2hhsxyamb.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwgeyouj.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gt2pmktiqzq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gt2szswixvj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hnayndyj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2hgwevlvo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2fjdaxbrt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gt2llzchlty.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gt2nkylzdzo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gt2vpshqtuf.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nchpjfdw.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gt2edupiahs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gt2xjnbzotd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2gpqabprd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zhltdwox.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gt2gjuzqiin.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gt2apunpeos.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gt2neygdiwv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gt2yxlapbem.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gt2pewpirih.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gt2tahhiyby.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gt2ygepvxew.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gidjowdz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebkfbtqo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nisdrvmh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gt2wopoxvyb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gt2jgqvpqif.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khfbkpoi.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gt2jjhlwasc.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gt2jtbbtklc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gt2hzetegwe.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2pzulcssm.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2ifoqdcue.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2hrsuuxfy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2cwbieqkf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.c1oappe.top/Article/details/gt2yywsnygb.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2amowacou.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gt2oxucjdst.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gt2saneohte.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2ysgqmxcr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnmtcgui.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2lvgxrbdb.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2tctifgeg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2hxfbtjes.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrithtw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2pkxmiasf.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gt2antatucq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gt2ljrgnpjc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ctnvstem.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2qisoankn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2cijtapbx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2igrqvikh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2zksvdmpp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gt2bbxpjzaw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2idwuyucc.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gt2fbbstfdg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2styprcwd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckusmwbp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgwflrwy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2joxsqbow.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gt2wdurlhrb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gt2yqoxnalw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekezgjfz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gt2anegocwe.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2ahkqejne.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpovddyi.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2ghpccdyj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2echhfwre.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2pjbufeua.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2lemstyqz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gt2chcrfzlh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gt2rbmybfhg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2lbzlqmwa.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gt2xzkjbuhr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gt2rtnrsewn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gt2zrpyxumg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2ayjcvrug.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkbxrduk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2uissyxcd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gt2resdcwoi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gt2khqymenu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gt2cupiczhi.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2wdqouoqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gt2tqmmyjqf.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gt2lotoxxbe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2tfkoafoz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2fuobdgua.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gt2fyyhdujz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2nkpkmhxf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2jfhrvrtt.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkmzcbjc.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gt2xnzbrywc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gt2ffrivcha.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gt2gxhxnvna.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2zagoxtqj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2hqwinzla.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2pgfvwwcy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2zzasuumc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gt2cdiowacb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2sorplovr.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2mypeucss.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gt2xokaqfxv.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2fhleecus.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2ohgpsayh.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2oholffmn.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2dnwhjtzs.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2qoopqjeg.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2giocwezr.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2uukcdbkx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2leayoyqq.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gt2vvwhhslk.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gt2cjifexbf.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2peodgfjq.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2gyolqnde.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2trilgqpc.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2gbasxpdt.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gt2jcmzkeap.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaxuatzk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2yilsargc.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gt2hmmhbsou.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiltgixh.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqxvhqrh.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2uarfydpj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2uezjgjqh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2abadjewb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2xxkpesqf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2petvfpxh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gt2yrpngjwa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gt2jvurpbnp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2jpqwzxxq.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2pocnltwu.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2osnyqfis.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ewcmhvvo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmngpwhw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2gpajaomn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjlulpki.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gt2zwxywzxe.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gt2kapfzhvk.html


<!-- 参考信息 -->