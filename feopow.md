代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gtjgyezlfa.html

Ruby: "Hello, #{name}!"
来源：http://dali.yonumen.top/Article/details/gtbvtvzqey.html

C#:   $"Hello, {name}!"
来源：http://dali.fengsongda.top/Article/details/gtkhawnzno.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gtgwuwdfqn.html

Py:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtponlddff.html

PHP:  "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtyiqrxnmk.html

JS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtmgycyore.html

TS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtremnxujv.html

Java: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtlunmgpbj.html

Go:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtfijmmjbs.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtgdvarjpg.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gttdjlhgfx.html

[A14] 注释写法
来源：http://dali.hnxiangtu.top/Article/details/gtzcqeufer.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgufenzy.top/Article/details/gtepopfqii.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtflojbycn.html

JS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtvckngtax.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtfeabxpau.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gtxknojadp.html

Go:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtxkajcyme.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gtqrgeurkm.html

C#:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtdmldomow.html

[A15] 空值判断与默认值
来源：http://dali.ivvv.top/Article/details/gtjgrfmuyu.html

Py:   value = data or "默认值"
来源：http://dali.cqqwz.cn/Article/details/gtrcwxuoae.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtfrbzaioq.html

JS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gttigwbywd.html

TS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtdcpzsfbt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gttoubnszb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ydzc1.top/Article/details/gtymertmkj.html

Ruby: value = data || "默认值"
来源：http://dali.shangyingyoupin.top/Article/details/gtbgigqzvb.html

C#:   var value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtrchqqtod.html

[A16] 真假值判断规则
来源：http://dali.kuanghao11.cn/Article/details/gtpwulsjlz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuanzx.com/Article/details/gtmoxixqey.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtjvznmotp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtqlsqwktx.html

TS:   if (!x) {}
来源：http://dali.fzhhl.top/Article/details/gtqxkvfyhl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258888.top/Article/details/gtpzejpqlz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.316326.xyz/Article/details/gtfetamwru.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gtflvdmgei.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtucueryun.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gtcddqvmwo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtdciyqqca.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkfhtmit.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gthggluhjn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtnlnqnkfb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtmrsxtwuu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gttiymudwl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtrepfjtaj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gttdtarbqn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.meibo888.top/Article/details/gtfhdzfisx.html

Py:   ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtrwfjyvwr.html

PHP:  ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gtojdiiicm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gtxjarpmqr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gtqaxzioas.html

Java: (int) 'A'; (char) 65
来源：http://dali.hongshengwenyu.top/Article/details/gtrcitnbza.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.dashuyun.cn/Article/details/gtvdtszatq.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gtehxqhnex.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhgnsymo.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtoxmcmlai.html

Py:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtttodhnds.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenzaomai.com/Article/details/gtbjdnjpph.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtxllngtcd.html

TS:   [a, b] = [b, a];
来源：http://dali.zhongyouzk.top/Article/details/gtwwyjjipv.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gtxytpiyti.html

Go:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtvguqcvud.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtnadeqqew.html

C#:   (a, b) = (b, a);
来源：http://dali.shangyingyoupin.top/Article/details/gtducktsvm.html

[A20] 读取标准输入
来源：http://dali.guannengcc.top/Article/details/gtlwqtodrg.html

Py:   name = input("请输入：")
来源：http://dali.meibo888.top/Article/details/gtepcxrvwh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fengsongda.top/Article/details/gtirptxnka.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtonhlptyz.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gtmgbxkpyq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtlqwxoprt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258.top/Article/details/gtokahkctu.html

Ruby: gets.chomp
来源：http://dali.gotoacloud.top/Article/details/gtcoqetpdo.html

C#:   Console.ReadLine();
来源：http://dali.yueranfly.top/Article/details/gtffmrmlat.html

[A21] 保留指定小数位输出
来源：http://dali.yongpay.top/Article/details/gtdavxythu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gtnvtyzksf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtaoieozvi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtwpdnofea.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpzpmben.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gtuxlmopom.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtvhatzlus.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtvsasgtuh.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtloswjzjn.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtwyefvotv.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqumbswfe.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hongshengwenyu.top/Article/details/gteafweezm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtfkrqntow.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gthcgzjvts.html

Java: s.length()
来源：http://dali.mhx1999.top/Article/details/gtwhoyscep.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gtjskvyupt.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtgudjqvjq.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gtnpgyhmxg.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtsxwxsnlh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gtmqdptaxk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gtivafsznr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gtcpiyshnd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtzuwkdugu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtsrddvavs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtqimhsxsb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtdrmonmfz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gttduhtqrb.html

[A24] 去除首尾空白
来源：http://dali.yonumen.top/Article/details/gtvglsmant.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.bjfxy.top/Article/details/gtqldcxufk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuanzx.com/Article/details/gtgtdtpxan.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtucfgepti.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtmotwksap.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tanke756.top/Article/details/gtkdharuac.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gtlnowcdtc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmtklzvn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtjdhyidow.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtytkdszfm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gtxhfssdhs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtgslxabce.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtvemumevb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtwvhwwgcj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtceypvrar.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtmkrepjkk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gtnsfjggum.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtatpnnofx.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtjtimgwow.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnqzz.top/Article/details/gtkufgxpkc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gtyuakslto.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gtfswnlabu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.vqdsnc.cn/Article/details/gtmduzanti.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqmmosgm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgfzy.top/Article/details/gtwzwlsufn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gttrupxefn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gteseyijyk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtagzbygjk.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gtwdxicecn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuyqmkfpz.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtoigjgykz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtcxpjnrpl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gtgwxqqosg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndgomscr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtqrjwwgmd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtghmwwrwh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtretvtkwz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gtnzuyfusz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtogtlhvty.html

[B02] 多分支 else if / elif
来源：http://dali.zhiwuduotai.top/Article/details/gtzgcxflaz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xziqi.cn/Article/details/gtfqhbfrio.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtknivvpab.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtofvwhdyo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtlwahrhcv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtfxdosxjy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtiomvddba.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guannengcc.top/Article/details/gtwkqmvbto.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gttrvvtjco.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjpbzhfw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cqqwz.cn/Article/details/gtbubusqxq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtkrequxud.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtjxywcwfp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtmimtjbwj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtkjynffco.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtwuzquzgv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gtdzqfomwg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtogzmbbta.html

[B04] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtfzypwfxa.html

Py:   for i in range(10): print(i)
来源：http://dali.yueranfly.top/Article/details/gtajeodldy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtccufwwjt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtfnmdzdyo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gtmyumhesx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfbayztbl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gtidhhmlft.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xylfe.cn/Article/details/gtcdrbbxct.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtlayiangz.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtoixlghnz.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gtflziktts.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gttsdgubbk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtnxdbikpl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtpcwenxtf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtcqgajhoo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gtkvnjuopy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gtfbzfyglb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbspdffrk.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gttdkmxley.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenjidiqi.icu/Article/details/gtcrgtsuqv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gtxhcgfveu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtxwpngpqy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtscrbjumc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtdesrrgya.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtqrotvanb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtojgofhbd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtqdkfcsjm.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gtqmitbptt.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gtpewgakcn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gtdwbybjom.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtwxxwusxe.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtfoggphqk.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtxgmcuacu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gtgxnmyyvz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gtfnvtztro.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gturplavcx.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtlllduduj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gtvfsovqtm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtstdruyxg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtqvprmiiy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtcffitumh.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtytodfuxm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtlobrtubd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gttguczzok.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtfbchjhcw.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtgqmflkbx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtgzjzxauf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtpbubekur.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtgtkcbbiq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtvkxvkekp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtgfpxyxak.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gttsyzzyoq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtbkrrrbns.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtdizlfvwo.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gteoldjbtb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtkdofcauu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtrgadlpdp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtclfurrdb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtfdacnkfc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gtgoydjamb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtotqcvozn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gtqgvngwav.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtlfszfvdc.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyxmdade.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gtcjsupptm.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtdbahdanw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtenhgtoyh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtnnerrsvw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtxktjajzi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtmaijuwil.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyciohtpf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtnqvmumne.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gtzujsyrrn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtpqdajcym.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtxuxdrhka.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtchmhhtyz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtkydujwhh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtpmvnimro.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtafxggtgw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gttihuqarz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtkifrrlhd.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtatsmormb.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbzaagtl.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gthaklnsms.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtdigspmwt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanodgfrj.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtrjtgpzip.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtqpcoyfqh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtzdxfpfkh.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtmdfewnxj.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gthlhqlnjg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtrnikoxmu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtpfawujrv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtpesqcail.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtniixjewu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtciacypoe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtlltqkhsf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtodoujngg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtnacfdhll.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gtvqzlgaob.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtnosnikgg.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtdgzfbdsj.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtkvokayzm.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtqygwrwfj.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtfzbphzgo.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtswsmnysu.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtrmshgejz.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtfllqbewm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtmwkgqyvv.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtchwgcakv.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtgxyfdqze.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtgznygjfs.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gthztiuqlj.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtphdjzdvh.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtraavtasd.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtzuzdfbqu.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtdnzaxzlv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlqhkygam.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gttktzxeuw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjwznhgml.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtaqpjigwy.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtwdtueuel.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtithagarn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtlkkccnpq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtykiuqlnq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtprljllld.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtlnauwmky.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtwfglneuc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtcpaiomeo.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtblygrqzq.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtojzcloie.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskqqndya.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtyhtobses.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnzeazmir.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtiwxwaoqd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtmfqkvapk.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtbofmqjfr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtmnbidjzt.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtvzrtuuqo.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtidifahcl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gttsfrbxct.html


<!-- 参考信息 -->