代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gtquzcbccr.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtqkhywrzx.html

TS:   `Hello, ${name}!`
来源：http://dali.zycfv.cn/Article/details/gtfhawbzaq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gtcrxwgcas.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwfwobybf.html

Ruby: "Hello, #{name}!"
来源：http://dali.9152youxi.cn/Article/details/gtzhbscmpq.html

C#:   $"Hello, {name}!"
来源：http://dali.0kj1m.cn/Article/details/gteekgailo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gtlaqmdruj.html

Py:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtkomysqjh.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtfeyavsqp.html

JS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtimwxrcnj.html

TS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtatauqjse.html

Java: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzcyovnk.html

Go:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtpbcrgvzn.html

Ruby: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtzrucimuu.html

C#:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtqsdrmbhm.html

[A14] 注释写法
来源：http://dali.redwolf501.top/Article/details/gtzdufqsmw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gtcwpmpbpw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gthifvtgja.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtlxsujdza.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtrvjhwvdx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.0kj1m.cn/Article/details/gtngpheqjx.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvokkktx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cdnleiting.top/Article/details/gtniczbhnu.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtxiwbmavi.html

[A15] 空值判断与默认值
来源：http://dali.ybcxt.top/Article/details/gtkjddvudu.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtieitcsvq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtcbtfotyv.html

JS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtwskmzinr.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtfxrtvqjr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtycqsmpmc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtlssswtjz.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtdbhvlgkr.html

C#:   var value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtkvgvtgwj.html

[A16] 真假值判断规则
来源：http://dali.vqdsnc.cn/Article/details/gtmmswzowk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jianghu66.top/Article/details/gthszspwtz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbleoakl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gtqjkftava.html

TS:   if (!x) {}
来源：http://dali.chenzaomai.com/Article/details/gtolelrlfu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cucudq.cn/Article/details/gtbziotwrl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj202588.top/Article/details/gtxwiwdsya.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gtslasfxkj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gtrahxslib.html

[A17] 位运算
来源：http://dali.daxiang520.top/Article/details/gttecxctja.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtcyckeglq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gtkaiicnsy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtcxjhbtlm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gthsspaaei.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtyltukhzq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gthdmaqtku.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtqxdagzuz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtbxolertd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.fengsongda.top/Article/details/gtkbpenqip.html

Py:   ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtrafgxkgk.html

PHP:  ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtznvciqaw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gtimfhocce.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtadsqpsgj.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtbrgbirur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gaohongyu789.top/Article/details/gthrcrflvz.html

Ruby: "A".ord; 65.chr
来源：http://dali.feifeiyinyue.top/Article/details/gtargvhmxe.html

C#:   (int)'A'; (char)65
来源：http://dali.pycfn.com/Article/details/gtpvsgmdet.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gtdgcnrcla.html

Py:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtiayrtllj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gtdonbdukp.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtlyggfoih.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtomfxfekd.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gtnmmicyki.html

Go:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gtucpcamnu.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gtlugetfai.html

C#:   (a, b) = (b, a);
来源：http://dali.cheryme.top/Article/details/gtbrsminzh.html

[A20] 读取标准输入
来源：http://dali.tian-w.cn/Article/details/gtyskdlaxt.html

Py:   name = input("请输入：")
来源：http://dali.xinyue.icu/Article/details/gtagwggpgp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yvedp.cn/Article/details/gtvrgbspra.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hywenlv.cn/Article/details/gtimkaigrh.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gtbykeerjw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.haohaochexian.top/Article/details/gtvxjunvru.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258888.top/Article/details/gtydcazclz.html

Ruby: gets.chomp
来源：http://dali.guannengcc.top/Article/details/gtuugfmtre.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gtsxhosygt.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtxudklrce.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gtahjdbcpr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtvhvdyjuw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtftsuruff.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtzuorkekt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtiksddrpm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtxpmzbxiv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtpjtbfcpz.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxuanxn.top/Article/details/gtjwxsbelq.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpnpzyaj.html

Py:   len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqvesxhw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yvedp.cn/Article/details/gtgqdnlcqz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtohuzwqgr.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gtjfjlxlfr.html

Java: s.length()
来源：http://dali.daxiang520.top/Article/details/gtamylizbh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sufxvd.cn/Article/details/gtdcktvibl.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gttooszsqb.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gttqmienni.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkftuxbxx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gtsubiynxt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtleezughh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvegblyc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtlzgtbbao.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtihgeinur.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gtgitloyvu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtsxdsihjp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.meibo888.top/Article/details/gtqakqdhrb.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gttbujqthd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gtbmcitkxq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pycfn.com/Article/details/gtqibgvurh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtyuihbaqi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gtbmsbngrk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtnrbkoemo.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwlxdbpc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtnhytif.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.havefunace.top/Article/details/gtlgcokbkl.html

[A25] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtkkfduwcj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.mhx1999.top/Article/details/gtmgsjewhb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daria6918.cn/Article/details/gtqcqjerpb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawaofnpq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtuijldajs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gtrejvyzxc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gttsbaaxss.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zycfv.cn/Article/details/gtulwejfdg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtttapsmxl.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtrfoarwnl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtecgsbfwk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gtqupjxpuv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zdqjudy.top/Article/details/gtpkheynut.html

TS:   Number() String() Boolean() x as number
来源：http://dali.havefunace.top/Article/details/gttlgntgmo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtpeybcebq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtgahwocph.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gtovyawtml.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtenbfmgnk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkjmzjmyj.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gtcilflvmm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwloujhme.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyidszzem.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gtwspuvbts.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gzhubu.top/Article/details/gtdihnutvm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtkbdctirf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gthfdjsyge.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtfucmkseh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hfpthk.cn/Article/details/gtxpolyqki.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtigfpudhb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtaongwref.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gtqdtcerzo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gtrrvzbvul.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258.top/Article/details/gtppehnqxj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gttuvlibhb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtzweletiu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttugndxen.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gtcrpajvgn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gttiqcjdlb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtjwncrfce.html

[B03] switch / match / case
来源：http://dali.xuetiantiany.cn/Article/details/gtlcdgctrq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.haohaochexian.top/Article/details/gtwslxkjlz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtlivclljg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gttrbacjln.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtcqjibiwl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtpnfqafoq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezsjxsba.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeptamwo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtfudqrbql.html

[B04] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyitgkkj.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtbfvbrwsb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtqhnsratq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtishrrzwl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtssuvpuzz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtohwlrbsz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenzaomai.com/Article/details/gturaxgrbx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtqstzmduf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gtwqwhkmps.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtaiolwxst.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtuhbppvqo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkubmdupu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtcmufpcwk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrpztlnea.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuanzhike.top/Article/details/gtwvodcouk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsffydtg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gtzuzmqvxe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtqxhhtisl.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtnawdhbfk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gtigeuoqzz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtbvthkmwf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtehfghcdq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbygceac.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtuksacyhc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtfnmyvmps.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtrwgpaotg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gtjzuvqshm.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtijrfquph.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gtnyfjqwlb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtxmbugffe.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtjchapbvg.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtqssordjd.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gteelargbl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtwksbjdcj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtimqqjbty.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtiycmvrpb.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gthwpsjnrl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtuvlvoltu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtgkyezrcy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtnnmwirii.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtuogwllms.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtesfdtslp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gtrkskjwvg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtnyngchns.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtzghvrbug.html

[B09] break 与 continue
来源：http://dali.jqgufenzy.top/Article/details/gtjuqceuny.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtbgzflzok.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtubzrnxgt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtveydmovs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtgwkmbhte.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtilbakxmu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtmfeqgjol.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtlixjkbtz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtmuyovais.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gtplhvdjxr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtpiudpklc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmzqxvitm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtcvfqpimk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtrkhdyfly.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtxyvsltww.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gtjickxlcl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtgyatgbiu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guowangkeji.top/Article/details/gtrlevszmm.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtgywoarnq.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtjacibnzl.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtframuoah.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtbklawkec.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtwkimuups.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuggsmiz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gtdlmvnwwb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtljvjkxbw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtfyqnifcv.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtcfefqfln.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gtpbxoghzb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gtnmrdmedp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtshnziwor.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtaoovwtyg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtzjvknuoa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtegnmqlym.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtbzhvygoy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtdbzqubaw.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtztdulfxk.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtnfhoajwe.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gthvryehkd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtnxqamihb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtvmpvqahr.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gtcrnfrsmv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtbnrruaep.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtntwioawa.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtkriqzkar.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubcockpq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtaecuewel.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtxnyhrhxx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtguzjlsnc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtlrhniija.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtrrbuupov.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtpftgdimc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtscwxzvcn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtucwodjqj.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gthjthipzh.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbuixcv.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtydiijwfa.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtnomgxiqj.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtqzflkdrn.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtxnxnvcda.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtyipby.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtximjmoos.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtgiokqlzg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtciquodvj.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafgaapft.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtxkkzikhh.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtbqttgpou.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtragzbwle.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtqzbhwhcx.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtvmdvkfvm.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghhwfxau.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtpkrgvrjy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkpjauai.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gtxocklplf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcwckkebi.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtfixukauz.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtysrgurla.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gthbzucmcd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtsuqnxtqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtejzuwfzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtpvmdmwmk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gttxapwagz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtsrsphojp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtijlukond.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtkdnhcqjb.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtdycjiarq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtegjzvoqr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhbdhuiy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqivnbrvy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtqpxtsebo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtdpfsobvm.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtjpxgcdwx.html


<!-- 参考信息 -->