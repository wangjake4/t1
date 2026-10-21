代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtnhjsztcq.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtsmjemmjr.html

TS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gttviaingp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daxiang520.top/Article/details/gtooxnaxfa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gtgagxauak.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtmzuszvvu.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gtymzdppgm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daria6918.cn/Article/details/gtosywioto.html

Py:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtucwpxjgq.html

PHP:  "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtsecbysmv.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtehkluouc.html

TS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtmndqczcq.html

Java: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcjzqvba.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtfzorwost.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtqoitztsf.html

C#:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtbcdsurxo.html

[A14] 注释写法
来源：http://dali.zhiwuduotai.top/Article/details/gtpeluebvx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gtgghcvheg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtmqvcricm.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtfsofghlw.html

TS:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtymfhexdo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gaohongyu789.top/Article/details/gtcviqsibb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gthpqxjebu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jianghu66.top/Article/details/gtzwoqkpmy.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqnoxrwm.html

[A15] 空值判断与默认值
来源：http://dali.nwbrower.top/Article/details/gtidwunxkc.html

Py:   value = data or "默认值"
来源：http://dali.zhengqikj.top/Article/details/gtiwrqvomg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtxbpftwqa.html

JS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtomtmguew.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtkhqjuvnb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangdashe.top/Article/details/gtmmvxrfpf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gtvtfjxiul.html

Ruby: value = data || "默认值"
来源：http://dali.redwolf501.top/Article/details/gtnarbmimo.html

C#:   var value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtwjxahlig.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gtgqztmbnm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aibaodan.cn/Article/details/gtosigomme.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpicukieq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtylbxfnat.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtecribvfu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gteqadmnkw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gtkhjqdlud.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenzaomai.com/Article/details/gtykrndigm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtshitomzr.html

[A17] 位运算
来源：http://dali.kuanghao11.cn/Article/details/gtryeiopyp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtgovvctmx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtfxbaioyz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtppknigas.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrzbskzwn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtfhjsqnit.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtjeijufjh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtpzjowqlx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtayxsntqo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tanke756.top/Article/details/gtjzcpliao.html

Py:   ord("A"); chr(65)
来源：http://dali.daxiang520.top/Article/details/gtfdqnajzi.html

PHP:  ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gtyduwpozb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gtapqqfhcv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwdxksmj.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgfzy.top/Article/details/gtchzafmkm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ehwqpu.com/Article/details/gtlmzanpjk.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtbljoxskb.html

C#:   (int)'A'; (char)65
来源：http://dali.shangyingyoupin.top/Article/details/gtwflksobg.html

[A19] 交换两个变量
来源：http://dali.quarkkingdee.top/Article/details/gtlajzjzee.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtoxsaxmyj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gtpuyxvogf.html

JS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gtqqrotsud.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtuklxohoy.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gtogjxczbd.html

Go:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcmnuvyd.html

Ruby: a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtclfjreek.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gtzjvjgqbw.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqwcihwd.html

Py:   name = input("请输入：")
来源：http://dali.wangshuangyany.cn/Article/details/gtiybrwiaz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gtsvfnhomd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.bjfxy.top/Article/details/gthujdjkvj.html

TS:   // Node.js：readline 模块
来源：http://dali.yanxiufei.cn/Article/details/gtcjwyxzvu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gttjnglzii.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ydzc1.top/Article/details/gtyhhnqddj.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gtkktzcyaf.html

C#:   Console.ReadLine();
来源：http://dali.yueranfly.top/Article/details/gtlguzizsx.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gtdcvxenee.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gtvlkhvbsz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtqfcuhyfw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtyyxpzqbo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtknpwdycb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gttgsediax.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtlulvcufp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtuimyqdrd.html

C#:   3.14159.ToString("F2")
来源：http://dali.tianlin.xyz/Article/details/gtyatajhfy.html

[A22] 获取字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtsvpkprjc.html

Py:   len(s)
来源：http://dali.hfpthk.cn/Article/details/gtraoigztc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zycfv.cn/Article/details/gtpybokmun.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslczoagx.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gtduilavma.html

Java: s.length()
来源：http://dali.sxryk.cn/Article/details/gtrdtenquf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtduxerlty.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gtsekicnrx.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gtubwglhbg.html

[A23] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtbmkayiim.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.redwolf501.top/Article/details/gtzvqvotvs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjedavfx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtcauwbudm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtshvvzthc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtawxhyezc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hywenlv.cn/Article/details/gtfjzemlwm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtitdsypge.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sysykeji.top/Article/details/gttrptbgqe.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gtymtoreza.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtlhwyywsa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gtpvkkeohe.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtghgpnppr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gticsklfoh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sufxvd.cn/Article/details/gtwrxedlgl.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtoxhhgupy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.9152youxi.cn/Article/details/gtvvuqyerb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpynwhrrm.html

[A25] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtfmaecgkt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gtvoiiyswt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daria6918.cn/Article/details/gtaourecoy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksncjcca.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtjdmriule.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxinkj.top/Article/details/gtbrkslwqc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtapwvvlxi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cqqwz.cn/Article/details/gtwhyebcth.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtoeuqnmgo.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtwzopnkfr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.quarkkingdee.top/Article/details/gtguclkaoa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gthajvzilw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtmernuhrq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gthurxezjh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtuwlkkzox.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ivvv.top/Article/details/gtyhbghdlu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtvekymfcd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtzicugxzf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvbgbhuqp.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gtjvtdbfdd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfovsmppg.html

[B01] 条件判断 if / else
来源：http://dali.c1oappe.top/Article/details/gtrgnfbbpg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gtpohxiomo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aibaodan.cn/Article/details/gtkptfpzws.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtmmjjxopo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtebkssleb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtpwbenmsb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gtapsfxeeg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtopxzsutp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gthsfcbrgd.html

[B02] 多分支 else if / elif
来源：http://dali.sysykeji.top/Article/details/gtrxzshfbc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.vqdsnc.cn/Article/details/gtcosrmryz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtdrjfcoop.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtywlbbikv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtrqqkrsrn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfmhyfsy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtcnspkejz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gtfladfysm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtfragzlnh.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gtjqkndbik.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fengsongda.top/Article/details/gtkwfbmyab.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtgikjncdb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtskjipuzy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtcabmmklc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtofjoxxdd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtylyxzmzq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guowangkeji.top/Article/details/gtnoenceee.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtqgprpxmj.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtuhtydeox.html

Py:   for i in range(10): print(i)
来源：http://dali.fzhhl.top/Article/details/gtwqlzphru.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtqohsxiym.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtzalkwoyy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtzndtgpqx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtyxeinpcn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gtxeghlcug.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tanke756.top/Article/details/gtavpbvxbz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gtzyrabfpu.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtzfhezmim.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznhrbofw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtkdxlfhkn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gthizzugam.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtsadpoyqk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gtoloyqrnm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtqwkwqwhq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gtuuunnith.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtisqjjwjx.html

[B06] 遍历字典 / 对象
来源：http://dali.yanxiufei.cn/Article/details/gthijwiuyc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gtslpvbdqw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqtpgrpx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtcvanixqz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtmnewsabv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtwfclyuut.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtxsgrhekj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gtxtmodnrr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gtflygbvhd.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtdxcjzeon.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtwrsjapii.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtalmazxle.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gthtekynxp.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtvmucobuh.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gthedbmyzq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gtjvaiupoj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtxblfwhuv.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtogxgdzle.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtrqesgois.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtizolhddj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtjttdjraa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtmrdhxbzx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtqbuyycyh.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdknrqvf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtdjpqismy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtyoydjqmq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtwhrkpjsp.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gtdmuhcejs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gthnonnhjf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtphydqaxh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtnuoesicj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvspepww.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gthrptfusi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtmbupuxvc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gtpkovqlkr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtbttqchdx.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtcywvsuzz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtbsqpbrjk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtpchlizld.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtiwitxfom.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtlpnuptto.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtvuksxovf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtbevbfdhw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtzdnmigre.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtnbovdhgl.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtkfrliarg.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gthtfzjztl.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gttxpcyudg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gthrvresgb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtnidmufdn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gtpezughbi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yanxiufei.cn/Article/details/gtxxpwpqrk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gtgecjsfrl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqocrozke.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtycvpafmx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtziocujfl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gthqsyuayn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtrbbotwbu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtqzdxjacz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtckebsmcf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtklycxjus.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtkduiqbdg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gtospwhzdj.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtqbohzodm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtfcjmacnj.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gttqlelsoq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtkkxsbynf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtainnvkge.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gttbyglfnm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtrzqovzvs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtnaeqleih.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtfqosjmcx.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtunimckjy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtjnrnioku.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gttwjasvxz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gttnexpicg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtbgtunhnc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjtozpcqa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtesbydtdk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtuilrbilu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtokpjoaqz.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhfrqyzg.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gtcohmgzjf.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtbtswxamm.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gttbsevtxd.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtgwllbjkh.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtgddgfyen.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtwmajgnph.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoizaalti.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtqphucpau.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gttniaxhes.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtreursonj.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtyxgbhqqm.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gthzhfpgww.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtieafctot.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gthwiowcup.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtwxlekurj.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtobvgwlxl.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtlbeygvzo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwodnapze.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtoirwvohc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthuaikali.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtpfjorlsn.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtdimndrmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtuhfsrodt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtzdzargpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtiukqshlr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtxpkdxzhx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gticieerdt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtxtldcpcq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtgmgggkxg.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtyayccdmc.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtoigjdhtw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtedpeunxt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtfaftgnrk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtteemhbgt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gthgqevtkp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtscemebcw.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtrdyrjwvw.html


<!-- 参考信息 -->