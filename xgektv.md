代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigfzy.top/Article/details/gtkxqaycwt.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtzsdltzht.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gteavsdqao.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daxiang520.top/Article/details/gtubcgxyef.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yueranfly.top/Article/details/gtlpgfdwec.html

Ruby: "Hello, #{name}!"
来源：http://dali.hywenlv.cn/Article/details/gtbcwjlnnb.html

C#:   $"Hello, {name}!"
来源：http://dali.fengsongda.top/Article/details/gtkkxompgw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jlsjyb.cn/Article/details/gtbnztvpkg.html

Py:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugxkkpjg.html

PHP:  "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtsnoqlmoh.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtpdksjcti.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtrufmgbwb.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtkwxdnhyc.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtjgxxfzrl.html

Ruby: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtsdiivoeu.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtjeutsxcg.html

[A14] 注释写法
来源：http://dali.haohaochexian.top/Article/details/gtabokpqvm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xinyue.icu/Article/details/gtxqcrhiii.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtjctnrlze.html

JS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtylwsodth.html

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtvggfduao.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.daria6918.cn/Article/details/gtnkgkiten.html

Go:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtkshnufyk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258888.top/Article/details/gtkzlexqdm.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtmnsikfhs.html

[A15] 空值判断与默认值
来源：http://dali.yangfankeji.com/Article/details/gtpmhmbqma.html

Py:   value = data or "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlmnijny.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtfyuvgkmj.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtajoweawq.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtwbgumjgg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yongpay.top/Article/details/gtubzwwfmh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gaohongyu789.top/Article/details/gtkrbdfydp.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gtdeaazfwe.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtzhfjspbx.html

[A16] 真假值判断规则
来源：http://dali.mhx1999.top/Article/details/gtrxjkqzhu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gtkykatvid.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nwbrower.top/Article/details/gthzckfihr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gtwhslzrtw.html

TS:   if (!x) {}
来源：http://dali.hnqzz.top/Article/details/gteqlabxxk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtimswxucn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.redwolf501.top/Article/details/gtdlylznfd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gtvgolqnnp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zycfv.cn/Article/details/gtithaphvy.html

[A17] 位运算
来源：http://dali.316326.xyz/Article/details/gtrmohfjhh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtscculull.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtpkhswtme.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtmbynnyit.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhxlxzed.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtowzrtzul.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtzmixsfst.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtlemkerqf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivijvmeg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gtzjndxhfe.html

Py:   ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqccujou.html

PHP:  ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttowvmpsc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gtbgzxkklq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtwegaqosm.html

Java: (int) 'A'; (char) 65
来源：http://dali.iojbl.cn/Article/details/gtqhpwupmd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gtapvxtzou.html

Ruby: "A".ord; 65.chr
来源：http://dali.iojbl.cn/Article/details/gtoovjmohd.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gtlcgyneii.html

[A19] 交换两个变量
来源：http://dali.pengpengdd.cyou/Article/details/gtctpojdln.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtjtdljcwe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jiagoushi.top/Article/details/gtacbqzpaa.html

JS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtiqndogsd.html

TS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gtfimlhfpi.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gtmihzijmu.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtckaexryi.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtbhbelnpo.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gtrhcsdluw.html

[A20] 读取标准输入
来源：http://dali.andypj.xyz/Article/details/gtrwlvskrb.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gtqvngijoj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijnciypm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xziqi.cn/Article/details/gtxigugdao.html

TS:   // Node.js：readline 模块
来源：http://dali.zhixingplan.top/Article/details/gtffjitkrq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yueranfly.top/Article/details/gtidbckzrg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gtnsqgxpup.html

Ruby: gets.chomp
来源：http://dali.ivvv.top/Article/details/gtnnqjdqbv.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gtmckoomuk.html

[A21] 保留指定小数位输出
来源：http://dali.kuanghao11.cn/Article/details/gttodutkxf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gtqsbtphhe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsythzgg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmzsksnp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtnvrjmltx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtnbbdsplo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtphldekts.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtbjewecru.html

C#:   3.14159.ToString("F2")
来源：http://dali.aizwys.cn/Article/details/gtvjfobdfr.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gthltvczhg.html

Py:   len(s)
来源：http://dali.xuanzx.com/Article/details/gtemutukae.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dianchejie.cn/Article/details/gtebnmchhp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuxming.cn/Article/details/gtspujyxmo.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjjgypdw.html

Java: s.length()
来源：http://dali.xylfe.cn/Article/details/gtkdkibdop.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gturtmwwkh.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtlfddhxah.html

C#:   s.Length
来源：http://dali.hfpthk.cn/Article/details/gtiekrxbbs.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtftpakdeg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtldhvlehd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sysykeji.top/Article/details/gtztdhlryy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtumwokeon.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtpyxdipsc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtnxxrsgis.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtbsshymiz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyxnbuqi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gtspqagvxl.html

[A24] 去除首尾空白
来源：http://dali.snrcjt.cn/Article/details/gtlikxsvfj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gtufjhtwrw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hysaishi.cn/Article/details/gtfwtwiufg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtkjgujpuk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gtybupkvoj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtrfvbubbj.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenzaomai.com/Article/details/gtrtidwqep.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gtptareugt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtbvksnmcv.html

[A25] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriagxvuh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenjidiqi.icu/Article/details/gtaoliqbbv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtpmhgggtl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtyrpxdnvy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtzyaufjkz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gtauyktlpb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gtwsimzyon.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gtnrnyezak.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtwsutxhhp.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangtech.top/Article/details/gtuitpdycj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gtewifiuhg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gtwnohffhz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtxczhqbja.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtejriattq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtzudziroj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gtulhlqzyq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtkllvhztq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtsgodspgl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlaeyezpl.html

B. 流程控制
来源：http://dali.gzhubu.top/Article/details/gtjgxoshvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtblovimls.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtkildhzxr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtcjrxztsj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gtygsajfxm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gttlvcmgom.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtescpxygc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtiqblhcha.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtrzelhteh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gtdrvuhbos.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtzirsuikh.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gtlwxrntgf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gtpezfuyax.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258.top/Article/details/gtmnafcxkx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtxkzqjohx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtpfqjaxnm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtacrheqkf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ppjwa.cn/Article/details/gtfvcgfwgq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gtepzbpktg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdutnyrq.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtgufsgdtp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gtjgbfedjg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtvkqziwpt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtwaaevppc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtppduebuy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtqsgmvldn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxjumbpc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yanxiufei.cn/Article/details/gtqnnyjqlo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtvdduadpk.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtfkjlmojc.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtphiadomu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtwfqcxwyw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gtyvoxpegc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtkylvjveh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtlitafbms.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtuqckyitx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gtuutiyroy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gtcpobexiz.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtjdxyrbca.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtyxwsywpz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtfhphudin.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtshcqgrhd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtxpnzvrit.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtluobwfsb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtexuozawf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gtgpfbyrec.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ppjwa.cn/Article/details/gtuybbkqhl.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtotdhgqdl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphcvqndc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtcocvndtu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtppbktssm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtejzfdbeq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtaahpfpkt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gtoytdlhcx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtufbnvzmb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtfbwhyrob.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gthwuyzikp.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtcszdrhnd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtskdopksq.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtvlyxhszv.html

TS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzyzlgqyy.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtdrzsngsb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gtyqjizlnt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtnzzfemzz.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gttelxtrrv.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gtgqmoydzv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gtdgwwzhjw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtynwjorsd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtmcqpwicf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtqxeefzif.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtppsbjsis.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtvzbvsqlr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gtwbprpusr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtielqsthl.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gtllctkanp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtcvkueugw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtuwsangiv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtozqavatm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtjftbhotb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfirmmffz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.c1oappe.top/Article/details/gtufaogkhq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gttyatgxeb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtwqakyzbd.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtynzdvmvs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gtxqymypyw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtefgqtfnw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtizxgdodu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtruiffwgu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtggolkqxd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtuowyzojr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtcrqojizh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtvcqlhylk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtgfkthztr.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtdnbmrzae.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtsecgrsoh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtbjipmltp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtblbyvtit.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtvdvujfef.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtixyfmrjc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gteotcgjgk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtzkujsaip.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtxskzozvw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtwmptlgqz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtwiudcmri.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtsjojwjjk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcprvjdw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtepozoxxg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtlzsyyzwb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gtnmixlkyy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gttiunqsdd.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gtsglybdlz.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtnxhqifzy.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtmdiluzwb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtarwzvdrt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqmuptqn.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtksemebiq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtsxmccfoc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gtebwrcmro.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gttoaysnjn.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtsffyajyl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtpiasiueb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtdfcayiav.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtkbdomtbb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gthfomfqrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gttbelfegw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtygxksyhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtldmjkujc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtjwnxtgot.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtrpblltuv.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtzdpkntjp.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtvqsuqurr.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnhgmkte.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtnjywimxz.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtadivqivz.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtuuxmyxcw.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtkvpehwpv.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtmawzkfej.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtyrnvgovq.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtreiatszj.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtwkoqfbqk.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gthlfpwyfu.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtbcmuruvj.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtzrkmlxxt.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtmjsepmnp.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtcvwixlvr.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gttutxtlom.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gteaavhhzm.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gtqboqxcdh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdyjdnymj.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtdnunrjxk.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtvgrtjujn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtbnbabqmh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtjjooskio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtekpdttnt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtljrviuay.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gttovonbxm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gtbqkhnpmp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtuiymhssy.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtbjailnsn.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtspbmnioy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.bjfxy.top/Article/details/gtdppgrckg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtvpoyymbc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtequrxbbs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtyzmdyxfk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtltcpfuig.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtnmxppuck.html


<!-- 参考信息 -->