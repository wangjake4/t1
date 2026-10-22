代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtircmfebe.html

Go:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtwsshjpzj.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtukzckbsb.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtybjnrwju.html

[A14] 注释写法
来源：http://dali.xuanzx.com/Article/details/gtuzezgdud.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.bjfxy.top/Article/details/gtjqteayye.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtyuhveikp.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtijoqzeom.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtprpcdckc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cheryme.top/Article/details/gttfpybafw.html

Go:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtfxmthtnd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenlongwang.top/Article/details/gtpwohpium.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtffjwbnpp.html

[A15] 空值判断与默认值
来源：http://dali.dianchejie.cn/Article/details/gtfamcbgqp.html

Py:   value = data or "默认值"
来源：http://dali.redwolf501.top/Article/details/gtxzocobgj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtnzlsmdza.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtlpjgtgwa.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtfrqneoqa.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.smart0.xyz/Article/details/gtosmteskw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.316326.xyz/Article/details/gtentkuohl.html

Ruby: value = data || "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtnumwlyas.html

C#:   var value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtigwbbske.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtvuibouzq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gtmsovldex.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxuanxn.top/Article/details/gtixggyxqn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtktuxvctj.html

TS:   if (!x) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteajaeivu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.c1oappe.top/Article/details/gtdqsunfzo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xinyue.icu/Article/details/gtzrggqilw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gtksecpxxz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gtzdtcmxgn.html

[A17] 位运算
来源：http://dali.zhengqikj.top/Article/details/gtcrtummzn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtahyzrfde.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gtylishrkf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtzvwgnskk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtdqgitkzx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtyxorekit.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtvnfnurgs.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkezaghde.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtrakzvpnv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gthodrzrci.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtqzncrcww.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtwubwtaje.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtynyavqjm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gtdtuprjyt.html

Java: (int) 'A'; (char) 65
来源：http://dali.cashguo.top/Article/details/gtyflonlia.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtqrjjkmnv.html

Ruby: "A".ord; 65.chr
来源：http://dali.xziqi.cn/Article/details/gtinjrecrb.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gtmibkuufj.html

[A19] 交换两个变量
来源：http://dali.cdnleiting.top/Article/details/gtwlfcgrwg.html

Py:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtkvbubfls.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zycfv.cn/Article/details/gtexhpvecc.html

JS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmystblxf.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gtmjsilpml.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gterbndylg.html

Go:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrbmcipu.html

Ruby: a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtvrljslkr.html

C#:   (a, b) = (b, a);
来源：http://dali.yvedp.cn/Article/details/gtfkguwgez.html

[A20] 读取标准输入
来源：http://dali.yangfankeji.com/Article/details/gtmxdpqqlw.html

Py:   name = input("请输入：")
来源：http://dali.yj20258.top/Article/details/gtncsybbcv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cashguo.top/Article/details/gtyxqjvnxz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtxbcwolfr.html

TS:   // Node.js：readline 模块
来源：http://dali.zycfv.cn/Article/details/gtopbwcsda.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gtbujkkzey.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gtjbfwxcay.html

Ruby: gets.chomp
来源：http://dali.shangyingyoupin.top/Article/details/gtqcgtppqh.html

C#:   Console.ReadLine();
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqctgpnl.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoipqtmjt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.c1oappe.top/Article/details/gtuyvnbzfx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtvksfpcsb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtjsxjizmw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtrckrhzku.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtgsehfqhw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdyeycwg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtoddvbhfh.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtcpdayszx.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gtanogixii.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gtfvlvvmik.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gthnwjqkxy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gthmxthhyz.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gtbzqqvdel.html

Java: s.length()
来源：http://dali.zycfv.cn/Article/details/gthnfrotnk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gtbytlrspf.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtjlwgbswc.html

C#:   s.Length
来源：http://dali.havefunace.top/Article/details/gtkphimpej.html

[A23] 大小写转换
来源：http://dali.sweek.top/Article/details/gtmbymieql.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aibaodan.cn/Article/details/gtdpsydeng.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hysaishi.cn/Article/details/gtjoeryniv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtguggdexm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscajbcwv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtzbwhhhxr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tianlin.xyz/Article/details/gtfubwfglx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gttqblrkol.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gteywoxhee.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtzytcagnp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aizwys.cn/Article/details/gthvhunmpy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nwbrower.top/Article/details/gthoyvghtv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtqewreplk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtcnoyuarv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yongpay.top/Article/details/gttaebqzee.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtpbmaxnvf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtoabkgmec.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gtghhrlhsy.html

[A25] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtekrhyvqb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtvexdenlu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gthmffepxm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtjboxhsue.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtiozjjbnk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yongpay.top/Article/details/gtvrqscqyi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtqxgsbmzn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gaohongyu789.top/Article/details/gtzphbgmkg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtaypkrxgj.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gtvuivtjsd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yonumen.top/Article/details/gtcdoqeaij.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gthalmwjnv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gtzdrqnwbj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yongpay.top/Article/details/gtafarqrmx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtssfafdzg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtxetqulhv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aibaodan.cn/Article/details/gtrzjxxbsk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtemblzqqj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttbezaoav.html

B. 流程控制
来源：http://dali.gzhubu.top/Article/details/gtntvowaco.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzagdpplg.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gtjvaldfna.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gtukaqngfh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gtjqfamxtj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gttvjbypyf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevsakpjm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtoklziecm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfiifvoi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aibaodan.cn/Article/details/gtzdmggnws.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtfavjzwwf.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gtkraxxvpc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtfecurrgf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtjzfqdetc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtihbgtqwr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gthhrfnytk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtoqvastag.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhongyouzk.top/Article/details/gtkfjpkwpa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtakejutvj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtnsfirzga.html

[B03] switch / match / case
来源：http://dali.chenlongwang.top/Article/details/gtelfdjgri.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gthdexeokj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtbqmypbty.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtilklvxva.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtcxiglpav.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtlfnjawmh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtalqjrmfk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jiagoushi.top/Article/details/gtdnvkwfoa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtrsowgfgd.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtppbjyuoy.html

Py:   for i in range(10): print(i)
来源：http://dali.ivvv.top/Article/details/gtagyhbrqv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtfrtuqxae.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtwinnswat.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtbcrxleip.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuszrkvtn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gttqpmsaph.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gtwbfnumib.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gtrealbtwf.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtxfgrkpka.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gtlaujyuhl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gtdwyiqhje.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtzfvailvj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtliaivfsa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gtrxvdospq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtvqilpgua.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gtnnjqjdlx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtqvxilbbk.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtpsjhbekf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gtiuwkacwj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gttfhlwilg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtfsvbixnh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtnxydsfvi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtdtxnrefp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtauszhgye.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gtbgxksbep.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtalefuvjb.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtzyazivgw.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gtkjzezyxn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtbokunfst.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtpshrofxz.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtcwebuzbn.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtqalmnnul.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtcnzyogmt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtahxqykfs.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtbxljybem.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtpjggbfed.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gttyveaflz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtruarryub.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gttsxibpdt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtjacwtefr.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtebptxmlu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtgfjwtpgc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtyxuqmbly.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtzgmbzjqe.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtpuzxeegz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtpcftcmye.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtkrwnzeli.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbaxtadct.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtsmazdhjo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtteounugq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtmuvmtrsz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtmikipcto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhqipmhz.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtjougmxfv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtbuoiednw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtwobzospg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtjtlmusnn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtlvammdbs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gtdakdjtgy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtjytkouyi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtjbqmmiuj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gtzfmkszvk.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtvzwhizoq.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gtxlrulexa.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtsavczmms.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtapdctunu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtgdgucynp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtjeshkoas.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtolzqclyl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjsakntu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gtkwighdjp.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtmxtjzzkh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gtbvpcizjo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtjhkuivow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtuiddzvhk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtwqivgtqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtgswdcyml.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtiqqdcwrv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gthasvoaog.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtafhbywvo.html

[B13] 判断是否为数字
来源：http://dali.xylfe.cn/Article/details/gtvcwqoecb.html

Py:   isinstance(x, (int, float))
来源：http://dali.cucudq.cn/Article/details/gtgczmcjnl.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gthmrbtqer.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxufikemk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtrbjrjoty.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gtlioxvrrh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtkwffscyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtnxnlhqrk.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtagrpcmqm.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtngviagys.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gttwjhttis.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtyddinisx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtjhqeeswg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtuytpgltd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtskrimdub.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gtpootmpgl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtkwrghxuv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtmkhupdua.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtlvstqado.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtctbflgpd.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtryaqvuwi.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gteylhzmoz.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtjbxtlsgl.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtochkhvlh.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtbzubrqok.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtnwerpspd.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtqotqlumf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtcznsixla.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtahdmsuws.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtcxmbtinq.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtczgpqwnd.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gthossgcwx.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtllpwfqvc.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtjwyfthbt.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtbonvsemj.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtojvbjnmg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtomcwepri.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtyyqiienl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlnmcfqqy.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtxsmotheu.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtfmukmthf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtvllazotq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtprhvoaqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfjdnpevf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtfsghknlv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtsgxiujvk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtsmetgvkl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtkrvsesgi.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtyebhqikt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtvffkdxkb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtdrmgmdeq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtjgxrwkmz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtldjnkdzy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtssehppyd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtmnqfezwi.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtvodkpyxq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtmhxadwdo.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtbbjbqjtu.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtpvgyjtfy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtpmxjlrbh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gteibczuna.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtziwqtptx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtrtllsjlr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gthvhicvmk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtzhstwpbp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtiaytfmbx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtofyzyiwt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtfrenrnlk.html


<!-- 参考信息 -->