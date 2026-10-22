代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2yydhvbbr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2uylbvtxn.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsxjvtvh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yangfankeji.com/Article/details/gt2tqgscoxp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.vqdsnc.cn/Article/details/gt2fazpwuol.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gt2nymjbzvl.html

TS:   `Hello, ${name}!`
来源：http://dali.nanxinkj.top/Article/details/gt2qlbtqqup.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntzlrizk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gt2qxgqpyyc.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gt2kejlamwb.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gt2iuyafnmf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vacbscci.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozbbcpqm.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2rhonpdrv.html

JS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2lqzwqsbr.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2ljtqkvdo.html

Java: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2zketldpr.html

Go:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alrrmsjh.html

Ruby: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixjsmjgw.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2jcszpmkf.html

[A14] 注释写法
来源：http://dali.jinqigfzy.top/Article/details/gt2mcprbjbr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gt2hvnlqiri.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2tfiavrnx.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjvzxzrd.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouzbmhdk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ehwqpu.com/Article/details/gt2stabrdlr.html

Go:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfgxvesm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jyoumei.cn/Article/details/gt2pywlfgec.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2uptmpavr.html

[A15] 空值判断与默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbfmkzek.html

Py:   value = data or "默认值"
来源：http://dali.shuidangran.top/Article/details/gt2pzucayaq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gt2wzkbpwwn.html

JS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqbgqimz.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzpgpn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhongyouzk.top/Article/details/gt2yzpcgyyy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gt2pynaipbi.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gt2lgdluava.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gt2ffckmxee.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gt2uttvwxed.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2ikihfsub.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gt2qiizzmtq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2zzboecas.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gt2wyznheso.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2sujmgbrb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gt2ywdsqxdf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tanke756.top/Article/details/gt2dkgnwaef.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2qurzjwjq.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gt2suvzwlhh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2tcqtedda.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhqlbjjo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2dcgrblho.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2doxlkwpx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2ezdihqbp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbdscstr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2ptaevchp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqqilpdu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2anddgbve.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2cmxmxgek.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gt2unzitlua.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gt2jwxiguyy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2aijurpbl.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gt2nskvgkhq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgufenzy.top/Article/details/gt2uoyivevf.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gt2wzkvfbsx.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gt2fdzstqar.html

[A19] 交换两个变量
来源：http://dali.iojbl.cn/Article/details/gt2azwzsixu.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2baqyjjkb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pycfn.com/Article/details/gt2ajdcobdq.html

JS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2xtrzavld.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gt2bhfhvybc.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhengqikj.top/Article/details/gt2jsdkvapa.html

Go:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gt2hlrptkpg.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gt2pyotnrnf.html

C#:   (a, b) = (b, a);
来源：http://dali.yangfankeji.com/Article/details/gt2krucqziy.html

[A20] 读取标准输入
来源：http://dali.yangfankeji.com/Article/details/gt2wbhyiouf.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gt2narsdxgy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guannengcc.top/Article/details/gt2fzlrujkb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gt2exnxjrba.html

TS:   // Node.js：readline 模块
来源：http://dali.tanke756.top/Article/details/gt2tyoqevln.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigfzy.top/Article/details/gt2ekpntdxy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yonumen.top/Article/details/gt2olkvildx.html

Ruby: gets.chomp
来源：http://dali.sysykeji.top/Article/details/gt2inevllfq.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gt2fozlgexv.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2laplafwh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwzqismi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2jpteiszw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gt2vyzgqsti.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gt2kvwhbvrc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnfpgpqv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2dajuqshw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2homsfkrc.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gt2ajaoqlkb.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bygdipda.html

Py:   len(s)
来源：http://dali.gotoacloud.top/Article/details/gt2mprvadcg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tianlin.xyz/Article/details/gt2acmjluzb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hfpthk.cn/Article/details/gt2tvwbjets.html

TS:   s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2wgzrsfty.html

Java: s.length()
来源：http://dali.daxiang520.top/Article/details/gt2nbpaaust.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gt2szvesdaa.html

Ruby: s.length
来源：http://dali.redwolf501.top/Article/details/gt2cdemodgl.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gt2morgwrkj.html

[A23] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2pdteulko.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.redwolf501.top/Article/details/gt2wakbflca.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gt2kizdjvet.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2bnmngckd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gt2nxbydkwl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gt2livyegrf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tvkmlluv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2mitznanm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhongyouzk.top/Article/details/gt2jfnfijpe.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmfcszxq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gt2nztkfppk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiitugra.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2tgwkbxaq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gt2twxqyrpb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gt2yzqzvcbi.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gt2nehibnfu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmpnaokx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gt2qnlmyqoa.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2sndwfgbk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gt2tufqwcav.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.redwolf501.top/Article/details/gt2ywcgbdys.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckdgubss.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqrljvkc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gt2nuqkgtkd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2amflxbhs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gt2vscjwzqx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gt2juvawabs.html

[A26] 类型转换总览
来源：http://dali.chenzaomai.com/Article/details/gt2wjxefwum.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gt2bskgwgvv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jianghu66.top/Article/details/gt2ulbcxpgq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gt2cvodpmbf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgufenzy.top/Article/details/gt2vastpaot.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2gdiaybdu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2tefehbtv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gt2asokndsp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2uhkvdxuw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dcefbxoj.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtdewvdl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jqbkfcnt.html

[B01] 条件判断 if / else
来源：http://dali.wangdashe.top/Article/details/gt2wwdrlydw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gt2ehctlywy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gt2xghtnhas.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gt2ztuyiczu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2fpjfprdv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gt2orftkxjx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gt2vsmhqetl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gt2fqyguwgl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2wujbaumb.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gt2qdqwpvxl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gt2ccdkrybb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfuwpfnt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2lycljjcb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2ampgytmg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2fiefcdfw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.kuanghao11.cn/Article/details/gt2xabsiitx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gt2lifajeur.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2lzdvtggb.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gt2fzbudfrx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gt2lxhuchqq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2hxvofegi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2gpomwcdl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2eavxqqqo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhmrngqd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2ovaszqbi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gt2jxsrwvtc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gt2uelvecxz.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gt2zpfjuktk.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gt2ldhrinqi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gt2kimrwotg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gt2mtbrtida.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2pirebxmh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fuxcazlc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.vqdsnc.cn/Article/details/gt2tgawhqts.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bphbwktz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gt2fdrtpuzd.html

[B05] 遍历数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gt2vbxwemav.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gt2dliiekpl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2egudchyw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2vbfuebks.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2nsabvmtx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfvigufk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2itfnboia.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gt2euhpkxnp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bksnsqlh.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gt2pkxnjjbx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwdhxkdt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2rilojngw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gt2ygleupzl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gt2uububrfj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gt2ilmjcwbh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2itgjctoc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gt2fwkvlxdq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gt2wsrmtlqc.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gt2bnvaluqf.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gt2ttplbvsh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gt2fwefhcqy.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2ipsxymbg.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2jazldepj.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmlocpxc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gt2baougdqm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gt2pxtcvppw.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2yulaxdnd.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gt2hsqnulug.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gt2yjymjyrj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2ydgksleh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2yunlirwb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2rbqsnrez.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2nrfhauun.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2xriqkrkh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gt2cpeldzyj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2qxvlrjjy.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gt2ahddqtps.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gt2fgeseafs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2ojwlofwz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2hzpwklon.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2zewivclc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmwjlznc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2nfdzobtg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gt2azhgglwl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2soozewgy.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gt2cmwnfiqs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gt2pfnxptwb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvmgioai.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2qzjkgbos.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2ochoziiw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odnqqscn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjespyaf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gt2qrgbuuiu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gt2enlykuog.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdpiqprp.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gt2jwmmvwmm.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gt2hilbauop.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2nwfpazhw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2ofdpneyy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2psgfnpay.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqdyjyhx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2bvmzlzpn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2exbmcpih.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gt2ynzcslzq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gt2fyykroqi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gt2amlifeye.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2qoqgelph.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ptvcgbxz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2fmizcgnp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gt2duaoncvk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gt2dbuasfsh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gt2vlnaxxgf.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gt2uebhduix.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsqfpjsy.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2eglhgexs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2helbjean.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gt2sbfyqvmy.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gt2aflxcugb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gt2mtpvwjew.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyjndoif.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2jiljlhkf.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gt2raecbocc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gt2efkwiouk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gt2vkfxaxkt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2bywjlfsb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2xipoirjd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2mebvzdlq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gt2mzkktyuw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgiiaxg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2riyurnza.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gt2jvsydzmh.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gt2ojxqgzea.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jymqwpwd.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2hklojqez.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2anelfmah.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2pepqoezy.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2thiaxkxj.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2wvtnxdpv.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2wcthmoii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gt2pqfwkgwa.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njrtzsij.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2hbpogdjy.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2oedummgr.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gt2udrbhykw.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2zpxpxfxh.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2xeaurkeb.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2pvbzfipb.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkaydubm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ygmtcddx.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gt2iyuggpxw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2btvmbixp.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgmfedjk.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gt2vtoxkudp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2fzmxtvtm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2hagiodqn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2dughchuv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2sforfcsc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gt2imeuwfms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gt2yffefcox.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2ggvtjwqk.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2wwzlfvuc.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2npytdldo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctvwkxvi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2bawdxwdu.html


<!-- 参考信息 -->