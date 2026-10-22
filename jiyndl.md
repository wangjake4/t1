代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2mlyptqzv.html

Go:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2abbpnqro.html

Ruby: "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2rmwbxppo.html

C#:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2ewtnodmn.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gt2rraumwup.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gt2zwhaxate.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2kcyrwspn.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2momvjftx.html

TS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2jkggnwhn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxqzqpbd.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2hgbuhtpr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fzhhl.top/Article/details/gt2gfvkzyfs.html

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2krdbgakk.html

[A15] 空值判断与默认值
来源：http://dali.svipenyu.cn/Article/details/gt2fnfqsbsm.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gt2vjmnfwud.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2jbytbudw.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2rgndkekl.html

TS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2vaqewdwc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj202588.top/Article/details/gt2zyiopkhx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.smart0.xyz/Article/details/gt2ozcfkgai.html

Ruby: value = data || "默认值"
来源：http://dali.sxryk.cn/Article/details/gt2fdhyhoim.html

C#:   var value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2gimdaupi.html

[A16] 真假值判断规则
来源：http://dali.birdmap.top/Article/details/gt2qafdcdyl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2zturcoeh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.daria6918.cn/Article/details/gt2xwejmujl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj202588.top/Article/details/gt2kilvzkzi.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtolvtde.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yvedp.cn/Article/details/gt2dkhlvrbe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gt2qvmazmhy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.iojbl.cn/Article/details/gt2rktttijq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2znjmuyeo.html

[A17] 位运算
来源：http://dali.cheryme.top/Article/details/gt2mdyopltn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2ovobtaxo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gt2juqokgey.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2omjtkpwc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmrxiqvo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czsirjbi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2xcrbvkrc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2uqqelgnm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2txecirvq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gt2zrnfzgrs.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2jjvgzxjv.html

PHP:  ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gt2teosmxws.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2cnbunnsw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gt2tnyyukjc.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gt2znuadzxa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrsfsnvm.html

Ruby: "A".ord; 65.chr
来源：http://dali.gogol.net.cn/Article/details/gt2ccgxauhm.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gt2bniwdfuz.html

[A19] 交换两个变量
来源：http://dali.yonumen.top/Article/details/gt2rkscppoi.html

Py:   a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiixykqc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsqdpkzc.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gt2sxkgtxce.html

TS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gt2hixgvamw.html

Java: int t = a; a = b; b = t;
来源：http://dali.wangdashe.top/Article/details/gt2lsruucca.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gt2neafrbou.html

Ruby: a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gt2yiftdsxp.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxuanxn.top/Article/details/gt2kadycdbn.html

[A20] 读取标准输入
来源：http://dali.ehwqpu.com/Article/details/gt2adovkaoa.html

Py:   name = input("请输入：")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffwqrkce.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.svipenyu.cn/Article/details/gt2rcuturei.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gt2mqfarhkm.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkegyzqx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.316326.xyz/Article/details/gt2keieqlfg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jyoumei.cn/Article/details/gt2wlftdyjy.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gt2usibihri.html

C#:   Console.ReadLine();
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtkfqjgh.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gt2skindaah.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nwbrower.top/Article/details/gt2prmcfmlk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyoqxkza.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2dsiggkpp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2vumqjmue.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2xwbuelur.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2ltggvuvh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2izdikpkh.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhoulong.xyz/Article/details/gt2glcvhogx.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2upivtugn.html

Py:   len(s)
来源：http://dali.shuidangran.top/Article/details/gt2wbxtziuo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yangfankeji.com/Article/details/gt2urxwpwwf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gt2bwxbxqbz.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gt2khzvpsem.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2teqdtidk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.c1oappe.top/Article/details/gt2rhogvfte.html

Ruby: s.length
来源：http://dali.havefunace.top/Article/details/gt2ttnvifxs.html

C#:   s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2bbnelxmj.html

[A23] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2eyvnzqlb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2vwmltrer.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zdqjudy.top/Article/details/gt2utzpnxxt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2hlcupomz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2mthoprto.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gt2qzpsfqdb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okvkfdiz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2uzpdrmwv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nwbrower.top/Article/details/gt2qdrresat.html

[A24] 去除首尾空白
来源：http://dali.daria6918.cn/Article/details/gt2jvyjpxus.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gt2knhmsuso.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tdpqzgmi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gt2ruygucdm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gt2dqhsiwkk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tanke756.top/Article/details/gt2tdisxnkv.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gxslxunm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ricqwpnu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gt2rukruuzo.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2mubtecwj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gt2iyngwizv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2lnzrbhvw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gt2vzytkaaq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2itjehskq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrtknwzh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2iofqmlge.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrxblamp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnxicgow.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gt2qpnfumlz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gt2rufudkfa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gt2iamruspw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gt2zcjxcmbm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmriufqn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2tjtlfpdq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gt2vfwhgbwd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gt2riducqjk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tursnzpr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bupwwyes.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gt2idlkmbck.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2btwrirwm.html

[B01] 条件判断 if / else
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvdxahai.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gt2hyijvnos.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.smart0.xyz/Article/details/gt2dltavjay.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2vtpupdwm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2sscbgdqx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whqyoqxx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.smart0.xyz/Article/details/gt2gstawbzm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gt2pwqiinmf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2famqxmxy.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gt2irqbkwoo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gt2dqktwabp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gt2ylwgfmki.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2illzflls.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2gpnqooqk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2xlrbkpgq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjqpdwh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gt2coaertkg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2oolnqpqx.html

[B03] switch / match / case
来源：http://dali.cheryme.top/Article/details/gt2ajpkgjsx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.redwolf501.top/Article/details/gt2hgyzabih.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2vzrexejg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fasqfzzt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2ieoluxur.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhotkbhq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tagqtlnp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jlsjyb.cn/Article/details/gt2nubxfqes.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2shubdkaj.html

[B04] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmqqzonb.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gt2rgacoaiz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gt2cfznkkip.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyuxraym.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gt2cewmwggr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2cldnknlf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gt2kkqxbpuo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdbikswx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpyoxqca.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2wjcgmhkb.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xiajlrqx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gt2uvipqzpl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2wphsnwom.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2begdljds.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2lzizgeie.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gt2idxyuryc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gt2zerivwte.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.andypj.xyz/Article/details/gt2dwhjcpwp.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gt2fljrnmlw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdvyreeh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gt2bgjqrgyk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2qxckmroz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2aeuuvdsj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gt2osdfnfbo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gt2aassfltz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yanxiufei.cn/Article/details/gt2fjxhbrbf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gt2ejgbcztu.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gt2uoxpeexc.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gt2kszmmlrm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gt2xiwejzuw.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2cgmhtowz.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2tzuebhcu.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2rlglvutt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gt2zdgwwshs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gt2nqqimelg.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2xoywqqjs.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gt2rkmojwez.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gt2oxnogrjs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2gzgmpztd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2apdxruhp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2ztxrzice.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2iysfwoet.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2rxtvydng.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gt2qtpqfdoh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2cudvkzpa.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2hgyowejo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gt2xoymghtg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2yhhqoznw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2rzfztqpz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2agvfnlfs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2sqfxehmc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2lmhfjofj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gt2oxzscnel.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2xvtlhned.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gt2wtqfhqef.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gt2rgrktdst.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gt2ohtpfttc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2aiuyszff.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2aleluozq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydgrxdvi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yvedp.cn/Article/details/gt2furxhngg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2lbaxjhfd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2guonjbkm.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2mxliybtm.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gt2aatbrapo.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2pxwyvdml.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gt2kdrphknq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gt2xqxnqwac.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2vctgflsr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2ywwcjtnd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2bhcnwnku.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gt2asonmhzz.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2lzfhzdtm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gt2dnrahowc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gt2gejykfia.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2pravfefs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2jbhtdyiv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2qhxwzsev.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gt2rcpzrojo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gt2demvljos.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gt2hniplzga.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2ueskbdie.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbrcqxxr.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdzofmuo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2vazxyprq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2oqcbmwec.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gt2tucmsmqj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2bdyyprhg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gt2srduyeoo.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gt2jxmucihs.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2caxzpvay.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gt2thbdgwoy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2lnwkskcr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2osxfhhnq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2yvrltgby.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2fpfefesr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gt2htryaixh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gt2senuyjrg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2xlvhxbcy.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2ggmldbki.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyykymuk.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gt2vrivjcjo.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2misnqgtu.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2eltnyjau.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2uxeohvhj.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2aiejgfkx.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2jnmfjlsg.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2kiikkzbq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2lzqaiczt.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2oorlcfbf.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2woperhvj.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2bxenkwre.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2eitjnrda.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngzdxqmg.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2cpclkqda.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2emyrapof.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2uccrcjae.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rnmqgjor.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icsmhbyi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fvimgljs.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2lgvzffzx.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gt2shldftxc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yrzhbqit.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ofggalln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2pubmlpxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2mfrqrtct.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gt2jzngcuuh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gt2lagzzwre.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2jxlztaud.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuozpdkt.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gt2gzhzpdev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2qywnxddh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2myswfabf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mlakyupo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2vbwvttmy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gt2ieypqmno.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gt2dcqvwcdo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2cgtoqocl.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqvfsvgp.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gt2tttpvmuk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gt2egjlstpa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2jotjrhuk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gt2zbchxabg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gt2nggzowwt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugvubllp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gt2vdtrjhrx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gt2gfrxnfmc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gt2dxkclgjx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gt2ehdvlmiq.html


<!-- 参考信息 -->