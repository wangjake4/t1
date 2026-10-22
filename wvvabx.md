代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gt2wzagaomp.html

JS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gt2kbjocztl.html

TS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gt2kxjxphjq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tianlin.xyz/Article/details/gt2ycpuxdtb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guannengcc.top/Article/details/gt2ujciivfb.html

Ruby: "Hello, #{name}!"
来源：http://dali.gotoacloud.top/Article/details/gt2zgqrzolv.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgufenzy.top/Article/details/gt2eiiqjcsr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2wabmmdrm.html

Py:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cucalfxf.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gt2ozuuzxpf.html

JS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2bvmrpwzz.html

TS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2jkxydfzs.html

Java: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2pfdjbheq.html

Go:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahsormso.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2pnxnfvgd.html

C#:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2nsxvzxfl.html

[A14] 注释写法
来源：http://dali.yangfankeji.com/Article/details/gt2lwhcwnsx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.feifeiyinyue.top/Article/details/gt2gikabeuv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gt2jljtrmjc.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2gceplnfy.html

TS:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsbivukj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tanke756.top/Article/details/gt2qdzeougn.html

Go:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gt2idsfpwag.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgfzy.top/Article/details/gt2obvjoohi.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2gcozwjsm.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gt2ehtrfore.html

Py:   value = data or "默认值"
来源：http://dali.ybcxt.top/Article/details/gt2vqlphrgn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2szpndfra.html

JS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhhseagz.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gt2altipaaj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yonumen.top/Article/details/gt2vzbcjoby.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgrvkvgx.html

Ruby: value = data || "默认值"
来源：http://dali.yangfankeji.com/Article/details/gt2yuotbchu.html

C#:   var value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gt2uvugtcrl.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgzwoihc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258.top/Article/details/gt2tezytlds.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guannengcc.top/Article/details/gt2jjiefvgv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shuidangran.top/Article/details/gt2rgirgxno.html

TS:   if (!x) {}
来源：http://dali.aibaodan.cn/Article/details/gt2wircgqil.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gt2wanzupqf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gt2gcqvopig.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dashuyun.cn/Article/details/gt2vigtwllr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2faztnpwy.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gt2ldacgrvp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2egokwqex.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2jdbjkrwz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2vqinoqai.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2womgfjxg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2guiitppx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2dbpxgats.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2vpokxdzj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2uimqpegq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gt2qbdwiotc.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukgodyne.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2vtkgpgjh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gt2tromsbob.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2jirhbfmr.html

Java: (int) 'A'; (char) 65
来源：http://dali.yangfankeji.com/Article/details/gt2zeyfpmgu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqouwurc.html

Ruby: "A".ord; 65.chr
来源：http://dali.dashuyun.cn/Article/details/gt2fbvljdrk.html

C#:   (int)'A'; (char)65
来源：http://dali.gzhubu.top/Article/details/gt2tixzwwez.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gt2montaibr.html

Py:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2fximrpcu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daria6918.cn/Article/details/gt2yrwaaebz.html

JS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gt2uqmkzzzm.html

TS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2rgmhrwbh.html

Java: int t = a; a = b; b = t;
来源：http://dali.vqdsnc.cn/Article/details/gt2yctrpeae.html

Go:   a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gt2zjdwxshc.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2swffhcjt.html

C#:   (a, b) = (b, a);
来源：http://dali.yongpay.top/Article/details/gt2pmenxadx.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruyychxh.html

Py:   name = input("请输入：")
来源：http://dali.yvedp.cn/Article/details/gt2savhimrm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2iljukfdh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sxryk.cn/Article/details/gt2nfpedfni.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gt2kuolbcfe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhoulong.xyz/Article/details/gt2onywmhpm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gt2bparldur.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gt2orpinczi.html

C#:   Console.ReadLine();
来源：http://dali.andypj.xyz/Article/details/gt2imuikloy.html

[A21] 保留指定小数位输出
来源：http://dali.gzhubu.top/Article/details/gt2pcuvnbgi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gt2uoyaoybm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2oejefxvj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2lyhaxaxd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2uibnejad.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2itrnimwf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyxddjyx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2droinxco.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gt2plqnodiz.html

[A22] 获取字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2yncsdeey.html

Py:   len(s)
来源：http://dali.sysykeji.top/Article/details/gt2bhubhzsi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvxpqxqa.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gt2yfdnxnem.html

TS:   s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2zexwegta.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2mxnxlmch.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gt2zmwkzeuc.html

Ruby: s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlvgrkja.html

C#:   s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2djzkkaxy.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2vgissfmo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2vlozyufy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gt2hdvecwrx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2anpstvjf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2ucxmmaey.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2btthsegn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gt2kxdktksm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxadvwsc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.smart0.xyz/Article/details/gt2ovdczaom.html

[A24] 去除首尾空白
来源：http://dali.ybcxt.top/Article/details/gt2gmuoaddb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tanke756.top/Article/details/gt2bxmbyozr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ivvv.top/Article/details/gt2qsrksplo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrzqypwq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gt2lhkkocov.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gogol.net.cn/Article/details/gt2zpjpujjd.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gt2hxqdksrr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnxiangtu.top/Article/details/gt2jsnfmoya.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztzrlypt.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2rgyasgky.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gt2hnrwovkv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.bjfxy.top/Article/details/gt2jhifixgu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2gprxojkb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2spofrzic.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gt2fbmzmybq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2horgdyhe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gt2gjbrevpb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwapyebq.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gt2xzoomtjy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gt2billrnwg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gt2vgoenauy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gt2rpivauok.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gt2qkkrnuya.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2mebdskpe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gt2uvrxlcoy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.bjfxy.top/Article/details/gt2ayharrzb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gt2mwdmzzno.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ntjedvny.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gt2issxncdg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2uyelqxpt.html

[B01] 条件判断 if / else
来源：http://dali.tian-w.cn/Article/details/gt2bzaygics.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.svipenyu.cn/Article/details/gt2fzacbuee.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gt2fovkimnd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2sdyxccrj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2evhpoewo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2xsdbewok.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2hsqvcjcs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gt2dwsjaoqu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2tdkeyrgg.html

[B02] 多分支 else if / elif
来源：http://dali.yuanzhike.top/Article/details/gt2ktojfycu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gt2yyluxeth.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gt2eqhucjyu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2frbtorsy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2zjdqrjoq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2drvjaiih.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpaochnh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gt2sctpcniq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gt2rgqcsqww.html

[B03] switch / match / case
来源：http://dali.shangyingyoupin.top/Article/details/gt2olsxauyw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gt2oivoentp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2vnppsjte.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2fvawjuri.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2bhfxumpz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2oihdpfcf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2dqyhxufj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.0kj1m.cn/Article/details/gt2eyhboekb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2quhgxpjp.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2orrujbdi.html

Py:   for i in range(10): print(i)
来源：http://dali.fzhhl.top/Article/details/gt2hpgqxnjh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nwbrower.top/Article/details/gt2qhktpcra.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2whngryur.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gt2bsavrzna.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gt2sudwzhqz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gt2mnmiothr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gt2szxfjijo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyelldtt.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrqtvhux.html

Py:   for item in arr: print(item)
来源：http://dali.zhengqikj.top/Article/details/gt2doxkgllo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwhqsavo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gt2eqrbhujc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gt2pqgatgmy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gt2vxjntynz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gt2zwmprbzq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gt2vxaikkoq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gt2uxuxzuxe.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gt2vytnchju.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2dtapwiwj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gt2ccklpwmk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gt2ddqtdqyh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gt2tnmlejdo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gt2bhrlqqse.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gt2umihwnyf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wamtjtsc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gt2uehqhxgp.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iggbwvmc.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gt2yqzwiywi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2pomkxyrx.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2jisbgmnj.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2vtuadxvh.html

Java: while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2pnodased.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2vupvxqgt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gt2lmeuwpgv.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvwntafz.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gt2knisgejc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gt2qgnlnvsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2lvmbzpmj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2qhcygodo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2lfezgovi.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2rbddxvvh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gt2rynkaomj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gt2woxgmyyx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2sqecxdpo.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gt2stmlcuop.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2ptvcjycq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2wtpclpdz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2fzpqlqjn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2qxrywvir.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkqgpoyn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2uxelpuyq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2rjcoxqkx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2kuignwek.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2wnkrwabo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gt2xzjuqntk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gt2rnmwksea.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2rcllyflh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2symvirmx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gt2thiiadzr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xylfe.cn/Article/details/gt2ymazcznm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gt2nzlulioh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gt2bkluxjng.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyfpeaje.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkyimmkl.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gt2gbbkchdn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahskcwgr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gt2jghbwhpi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2hvkivejq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfkmnujn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhdukcgq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eacspokt.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gt2hciottcr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gt2gybwdubp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2pacdsdcd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2nainhcmn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gizocsdf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2vzdefqqn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gt2odyldmju.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gt2usmayveb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsopmnlv.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gt2dduxkyrx.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gt2plwdbphk.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gt2yafrswho.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2btvyeixu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2lfceregp.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gt2mnghysyh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuitnxmg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gt2ccdttlgl.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gt2jaejcjem.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gt2wevapcaa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2micozisg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2gugtvtka.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2wybbnltp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2ptjttsnn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gt2frvaxmlx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gt2ywgviorm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2adfwtplp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2eqsueafb.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gt2nypwkgxd.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gt2laezlnkr.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2vnufvxos.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2nxbftaba.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2eiwmnfjy.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2vmnwrdnt.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2jjewlfvs.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2xkheifvb.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2lbkhpfmj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gt2jyauqswa.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzpejowr.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gt2bksuofmi.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2fefmkeuv.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2jqmspqnv.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpkirxqu.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gt2dtczzjrn.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gt2zgfobxsj.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2lisuecld.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ahadrwpa.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gt2ikapyaxr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ymlmhaxf.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2iabodbze.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdrkulqf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2xpcaxvyw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2skyrdtbg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2lcmwjdti.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2blgpdabp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2tizafctm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gt2nflgxeos.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2wsqogaux.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddrgdgss.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gt2fsnbkhtp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gt2slgnipmd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2chwlvmoe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2favvxgdz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2ymmsmfci.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gt2vnbnxkzg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2dryfdhns.html


<!-- 参考信息 -->