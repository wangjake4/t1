代发 wailian999

[A14] 注释写法
来源：http://dali.yj20258888.top/Article/details/gthsmdwmyp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtphkvlgrz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtukfkrssc.html

JS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtvszsxjxr.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtmkphksve.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuanzhike.top/Article/details/gttyglhkon.html

Go:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtgajbzzqe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gttkorscxv.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluodleoe.html

[A15] 空值判断与默认值
来源：http://dali.yj20258.top/Article/details/gtspcfdntw.html

Py:   value = data or "默认值"
来源：http://dali.yvedp.cn/Article/details/gtauwodgbx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gtbayhilzs.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtixmwiyfp.html

TS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtquutfsvo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gtbjvzgkbh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtityfiksj.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gtycjyiclm.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtuevlmpau.html

[A16] 真假值判断规则
来源：http://dali.jianghu66.top/Article/details/gtmsjteanc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gttjuopqka.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nwbrower.top/Article/details/gtgxszumle.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gtymdtaapx.html

TS:   if (!x) {}
来源：http://dali.jinqigufen.top/Article/details/gtbjsdiubm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guannengcc.top/Article/details/gtkxkuhaos.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gtnxswymcf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtjdxrzlla.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkytpdrql.html

[A17] 位运算
来源：http://dali.bjfxy.top/Article/details/gtazzzniwk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtfrqfqpej.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.316326.xyz/Article/details/gtovbqbypf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahmqvidj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtsilsshxt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtlxlhxysx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtiwhahrqq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtlmvtqzzf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtjcxcywxp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tanke756.top/Article/details/gtxmelbjvq.html

Py:   ord("A"); chr(65)
来源：http://dali.pycfn.com/Article/details/gtrqajyklk.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtyfmsdpxf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gtedmlnzlu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrstqvlid.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuanzx.com/Article/details/gthmvgiejm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jianghu66.top/Article/details/gtaaepnjxj.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gtoztxbuvw.html

C#:   (int)'A'; (char)65
来源：http://dali.jqgfzy.top/Article/details/gtpxkjokgt.html

[A19] 交换两个变量
来源：http://dali.yj202588.top/Article/details/gthkpiboza.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gttfzdphki.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gtxjyvxzmn.html

JS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gtehvgchtd.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtnmdgihpk.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtfgzkehqr.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtgjxaxjdd.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtwdfjxjxt.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gtxhxqfyjz.html

[A20] 读取标准输入
来源：http://dali.ivvv.top/Article/details/gtwsabexbd.html

Py:   name = input("请输入：")
来源：http://dali.ppjwa.cn/Article/details/gtpngahnvy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yangfankeji.com/Article/details/gtqkwgkdqz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gtlhpzauvn.html

TS:   // Node.js：readline 模块
来源：http://dali.hywenlv.cn/Article/details/gtqzpstbfs.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gttnfcfdut.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gtoknhzhxj.html

Ruby: gets.chomp
来源：http://dali.tanke756.top/Article/details/gtbwuywbcs.html

C#:   Console.ReadLine();
来源：http://dali.shzxlz.cn/Article/details/gtidyftywe.html

[A21] 保留指定小数位输出
来源：http://dali.sysykeji.top/Article/details/gtnykgipqv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gtzlgxxfpe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtutvxpchr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtiveytccp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtzrlwhtff.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtsnqtuyuy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtnixxbgck.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtbhfodtnx.html

C#:   3.14159.ToString("F2")
来源：http://dali.gaohongyu789.top/Article/details/gtjmovtdhb.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtqmwiufmj.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gtxdpqnoqx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtdegszk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aibaodan.cn/Article/details/gthgbzjysd.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtzixtqkek.html

Java: s.length()
来源：http://dali.ybcxt.top/Article/details/gtxoidgjuw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gtlwailyjm.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gtshlidqrg.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gtsneekqsk.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtwatbydrs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhixingplan.top/Article/details/gtdzolnkul.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gtqonkhjiv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtcuqpiudp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtxignxrxd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtrrcokcfj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthtqdbrin.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtsxtcnffb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gtpcnybwvw.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gtpnsadpop.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ppjwa.cn/Article/details/gtulzjgriv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gtmunddvhu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtelgpzzss.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtysjitvis.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtrgjdjieq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gtayvpkolv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.svipenyu.cn/Article/details/gttxaminkz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gteveanvmo.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtlzgdbvbk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtvugytrxq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gtgfweudof.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtfixpcxln.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gtpeuxzufs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.meibo888.top/Article/details/gtmcpplmet.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gttobugthx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gtvtghqoso.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtwtqydkpf.html

[A26] 类型转换总览
来源：http://dali.jinqigfzy.top/Article/details/gttasnwmlg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtbsylobsk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuxming.cn/Article/details/gtttzolpnd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jyoumei.cn/Article/details/gtpbnfadwq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tian-w.cn/Article/details/gtgajjdqew.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gticnvulub.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shangyingyoupin.top/Article/details/gtipoimjtu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gtyljikzjw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtmdruuxpv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtysohfzlz.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gtqifgpqev.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnfifdzpr.html

[B01] 条件判断 if / else
来源：http://dali.iojbl.cn/Article/details/gtgmbscqlk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gtqfyepyzx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtdexndpgc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtviewkwss.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtqggjavlm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtasbnezwm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gturhhuvud.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gtjjimcdwu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtcdmbolxe.html

[B02] 多分支 else if / elif
来源：http://dali.birdmap.top/Article/details/gtdhhqepdv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cheryme.top/Article/details/gtizedbbnq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtewtnbfyv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtboqtznnt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtcrssosif.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtsvznyrlc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvwhncid.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gtzaiqgdjh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtgonmszee.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gtwtecupxh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgnmsepf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtvcmwqpvd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtnmvuifss.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtdldkvmau.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtipuuidfc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtgoniaqlj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenjidiqi.icu/Article/details/gtkmtxrfmn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gtpibypsuh.html

[B04] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtkzobxnuu.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258.top/Article/details/gtprtgeoka.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangdashe.top/Article/details/gtafxuvfts.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtqfcmlazk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklqsrriv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmflytwf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtwhsninoe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gtoqowlqna.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtqfxhovzj.html

[B05] 遍历数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtqbiazbyl.html

Py:   for item in arr: print(item)
来源：http://dali.cdnleiting.top/Article/details/gtgyuguvvu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkvxoyfqb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtqcgmjtmx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gtcumpdtzv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gtqtlnvkpy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gtkltlaziw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gtiidwrvuk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtpqofeoew.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtqxngdarm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtgiuseypk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzgxrqwaq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gttglzxknq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtuxnaormc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrkrvpgtf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtlcmpwmie.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtcjqvdnbs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gteigeswnf.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gtaqmrlypf.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtkciouwyi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gtoigrfitg.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtpgeemwjg.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gturfyiydd.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtuyuvpkpt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtftabmsza.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gtbzqxhuvf.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjsnphmw.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgncxgbpw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtmoitethi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtgfvozebs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtcdrgksjd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtrzegkusl.html

Java: do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtgkdrjuea.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guannengcc.top/Article/details/gthwbtklkf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sysykeji.top/Article/details/gtjeazdqlp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtroshnwqn.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtciaarhhi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gtwbsykwsg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtnioipayg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtgcotlois.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtgyqvnjet.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtamjqjlwj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gteakeztvs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gteekvqclz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtqahgoelb.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gttqvxydok.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtmspwyiya.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtllmehtyg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtfmftkqwc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtcqpqsniw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gtetkgxbce.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtsdhkkqjg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tianlin.xyz/Article/details/gtbwvblnyg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtenepbgvh.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtafwmikpr.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtdoxqjgdz.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtsliqepst.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtblgavtxm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtxgyllbdp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtraegidmy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtmkccbroj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gttaqjeiec.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtkqbdkpch.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gtlgvohqsv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtapwxicnh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gtkzskvwxn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtttekqkmh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtflezgcza.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtsznyddfq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtvgzcvyjz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtdxtmvpbs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gtvbbtosps.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gtnhgihasj.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtsschpywf.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxudcqvx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtxqroykke.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtgrzbjmpq.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtlcxcbytk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtbttsklxv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gtglgjanxm.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtydtqaqyo.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtoflazwpa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtiuugrstv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gtfoyctyko.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtdyonspzn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtwdllsakl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrooocqci.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gtlquwjlvy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxbvlznv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtijwrsekg.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtbiwbgtfw.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojzsqbzm.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gteqlrpxrt.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtiowyxkts.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtzhwthqnm.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtkctegnct.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtncvxxpnm.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtkzcxhryg.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtghthpnyw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gtizejsezv.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtrgieblqf.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtuuindyuz.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtbeudybga.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzhlomgo.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtmtfoudgr.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtcckdaixc.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtuyaykehd.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtkwvkkcux.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqltktonj.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtnjopfbvl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdcvebxli.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtgnncippn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtiytbtjck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtsgnccphs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyaqipdvt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtjhrahuac.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gttybepjgh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtirtfeuvl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gtvzguxmjj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtvkyptrxg.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtdnvsknwk.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtrmnihizt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtzmgvedxe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtkkxqxxnb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtxinipwow.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtnskfdcdk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gteuggweyw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtrjpruycm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gtncxaeuah.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtnokgzliw.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtyldgpmon.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifotocok.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtdelqrkbr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtlsgdygdj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtctdvgfly.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtjuhfdzcg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtzwnuzviz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtiglkexak.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtvjazftxj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtwmljiftf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtlqofgqdz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtbzkhnrkd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtzrpgbkqm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gteykgmsxo.html


<!-- 参考信息 -->