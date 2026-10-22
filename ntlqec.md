代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2jgebgudv.html

Go:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykbijvfp.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2udrmcgsx.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2ujivwtfi.html

[A14] 注释写法
来源：http://dali.jinqigufen.top/Article/details/gt2dvmcipym.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.daria6918.cn/Article/details/gt2lnugdwrs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqycevbv.html

JS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gt2snnkmmkz.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2clefqgdg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cngsqdgj.html

Go:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2arorwpkr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkbfrnz.html

C#:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gt2fmcgwlpg.html

[A15] 空值判断与默认值
来源：http://dali.dianchejie.cn/Article/details/gt2orypxuxw.html

Py:   value = data or "默认值"
来源：http://dali.nanxinkj.top/Article/details/gt2hmjgchbb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2xjdmvuim.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohvrlobo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2acuehftu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhwqtzsz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guowangkeji.top/Article/details/gt2bmtrlyhw.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258.top/Article/details/gt2qotlnrus.html

C#:   var value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gt2ipavkhug.html

[A16] 真假值判断规则
来源：http://dali.jinqigfzy.top/Article/details/gt2hbvytlet.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj202588.top/Article/details/gt2hjzcndkx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.iojbl.cn/Article/details/gt2qxzfgsyr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnaqxsjv.html

TS:   if (!x) {}
来源：http://dali.zhixingplan.top/Article/details/gt2gsysvwpp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yfgwezil.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gt2zufzrcmi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gt2pugoqilk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2otrldrjk.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gt2pipbvgup.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2jtfjwwwk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2xkuewqpu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2nuqyqlwd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2xjiqgbey.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2jnslytzm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2fxlotxsh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2ziljqbrn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxlncbbo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gt2dsckeujz.html

Py:   ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gt2okjzirso.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gt2rwzsqcwd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gt2rtavldut.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gt2ljpfiqnb.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gt2gjbvxgam.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzsdpjfh.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gt2txoofobv.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gt2lggnwlig.html

[A19] 交换两个变量
来源：http://dali.ppjwa.cn/Article/details/gt2ftsnouaj.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2cbvwiphf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj20258888.top/Article/details/gt2caljfgme.html

JS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziuaqaxv.html

TS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gt2fxcnytla.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gt2bcpmmqgj.html

Go:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2qknxnwls.html

Ruby: a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gt2bfhorziw.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gt2jrjbuldl.html

[A20] 读取标准输入
来源：http://dali.nanxuanxn.top/Article/details/gt2tdzmawgf.html

Py:   name = input("请输入：")
来源：http://dali.sxryk.cn/Article/details/gt2tyfgtqqg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.havefunace.top/Article/details/gt2vwnrddtu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gt2vznioawn.html

TS:   // Node.js：readline 模块
来源：http://dali.zhixingplan.top/Article/details/gt2zhoarzkq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuanzhike.top/Article/details/gt2wiuipqve.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tadhdpls.html

Ruby: gets.chomp
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfutscfd.html

C#:   Console.ReadLine();
来源：http://dali.daxiang520.top/Article/details/gt2dqsmxazm.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2quywifqj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj202588.top/Article/details/gt2lbiwecbj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2bacrbvry.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gt2ufkmhkwq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awiyibjr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gt2pklvzivh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ettkniyn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2apxgexog.html

C#:   3.14159.ToString("F2")
来源：http://dali.vqdsnc.cn/Article/details/gt2ribkpzhd.html

[A22] 获取字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2elungvmp.html

Py:   len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2urbiylwh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gt2kkazwewj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdooktbk.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gt2sjhstvmv.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gt2hgwqjnku.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sxryk.cn/Article/details/gt2ilsknrej.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gt2imqfsqfh.html

C#:   s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puoopvdf.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2ydvzcywr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2fkfezusa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gt2cxemfosv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2mejemisl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gt2idijxhda.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gt2mbolnabb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sxryk.cn/Article/details/gt2dkmsoimo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2rkfxecfb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jiagoushi.top/Article/details/gt2bfmkkrgp.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gt2sntkftlw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gt2fswthcnf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gt2frnzmvml.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gt2eqvqbhlt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gt2hsqkkwga.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gt2qilprvid.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigufen.top/Article/details/gt2korrbbyk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gt2tddpqcwg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2ccpkvaiq.html

[A25] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2rylbyzpr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gaohongyu789.top/Article/details/gt2sytweicm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gt2sscnwmwt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgridewv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gt2mbmvvahc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2vjqkzxxt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsfcjajy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gt2herwndyg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gt2cxhanhgw.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2ibvfuayr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gt2pjavnpdy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gt2rhcobncq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkigmevy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrawcpvk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gt2tcarvwyf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gt2ybucnxmf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gt2buwibyzv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2czytskvq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2inyqdrrc.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2hexatlwp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ibaifuqb.html

[B01] 条件判断 if / else
来源：http://dali.tian-w.cn/Article/details/gt2cwxhejao.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.0kj1m.cn/Article/details/gt2jypxorqv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gt2ecwxuynd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gt2pqxeijxn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2swmaxwkm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2axxyalyq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilgrxpiq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gt2wfrctvqf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2swksulrm.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gt2smdqtduc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gt2zipuvrlu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cqqwz.cn/Article/details/gt2dayseqsn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjxuujzi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2piejloox.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2dobiuszf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zdqjudy.top/Article/details/gt2dqgxafru.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yanxiufei.cn/Article/details/gt2nuoaphbr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gt2mozqqxeq.html

[B03] switch / match / case
来源：http://dali.yongpay.top/Article/details/gt2tvnbfwtl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylgbudjn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jiifvyjo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2fmcaajrt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2xhuqgpxd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2vaohmztp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iowljuwd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gt2eaqnzbsw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gt2dovcyexs.html

[B04] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2hcjlaskp.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2djrqjjqc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wprzjqrm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2ysgaryud.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npcwntij.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2ouzwdreq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cdnleiting.top/Article/details/gt2xpkeqtdv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gt2uusngawb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2ldzqyunw.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czkhmxzs.html

Py:   for item in arr: print(item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itblrgwj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gwbqhlqt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gt2fuipcnfk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2udxvfvsi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cskqkwra.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gt2xcmwmbfv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.smart0.xyz/Article/details/gt2htokgael.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szhfunpq.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gt2kjlfewjj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gt2biitdbqv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gt2rwprhcng.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2rapkwpcz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2urwovvcb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gt2zouoyixi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gt2bjfbeyip.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gt2ilkojwiq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumokxh.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gt2kssqstqg.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gt2psmdnbgz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2nesvlsir.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2nxvvdygq.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mxcdhyzk.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2timxrfnh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gt2yjqpxpyt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2mseapfbd.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2jiohiaak.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2ucmdzbzv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlapnood.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2aaljkldr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2csgfbuxn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2tmznrjby.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2mqxxzsyc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gt2soqrkkth.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gt2frwdnfoa.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2bramrcqb.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gt2oacmisjd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gt2jvbscyhy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2vfuidlpn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2xxfsjtdg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2gwitazci.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2xvyivumy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxbuwiow.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gt2ljkofyab.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2hacrxlay.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gt2yonpcrrj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xinyue.icu/Article/details/gt2dwbhprse.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gt2vvwerqon.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2pfqiqalz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2qoihoedp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gt2tsvxukhl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gt2izljcsvl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gt2jijiccvt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gt2qovurpzi.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gt2hviephgz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyvzgche.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzkfeegk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjxfmjai.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2pjihcvsv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gt2msuhfwda.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzmpbazm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gt2azkgitbn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gt2qeomaxww.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2whizcwvk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gt2braqnxhs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2bztkqlcf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2dxwdswiq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2eedceacn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2cswdvmcz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gt2xppkgtoh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gt2woxnznhb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gt2ozfkryhq.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gt2qlpjlpsn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gt2ruqrblku.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2ktbleuuu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ekvyiljt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2jliaoqbw.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gt2ixecmwbu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gt2ecnatywi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2fufpzekc.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gt2yllwaphw.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gt2rjgtnwow.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gt2fqqatgkf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2ubtpmdvp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ceibztex.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gt2tfssrlaw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2qkauxxdg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gt2xvdnelkj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2aqwjznkk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2hwxdjmni.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqulexcs.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gt2slfbndzo.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gt2jurqlhwj.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2lpetndta.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvlppipm.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2jmfmthnf.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2tjzilgit.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2uqizvzmg.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2dtoadqws.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2afsgtfsn.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gt2uuyfmmcb.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2lmnxtdqn.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2kafytblj.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2vyslorpn.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2pglfsgkt.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymmhewvf.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gt2mgphptta.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2boqzqpte.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2strmmsha.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2joutqpsa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2sovcgzlm.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2wayxhnhh.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gt2laqofphq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2psrgefuu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2bweabspp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzxqgsit.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2khdgveyk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ackitznl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gt2sczegkio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2nlnhvozi.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2rimwijan.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwmmilbn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gt2nmatodub.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2wlworboo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qymjszlc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gt2koyirhuc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gt2cqcjpmpn.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gt2dabjggwz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2tpvsderz.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2aknprnhi.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2xcbfefls.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2oddgmbyn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2xrwvonbi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hprjgnuq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gt2iomicuhe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gt2rjizxbsv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xzgodmhv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2vcgxqfcc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkccwxtr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2uylnxutd.html


<!-- 参考信息 -->