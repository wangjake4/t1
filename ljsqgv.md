代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gtbmjrnjhf.html

JS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gtnbvsslqi.html

TS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gtiuskgqkm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gtuervcknl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdenuwhw.html

Ruby: "Hello, #{name}!"
来源：http://dali.ehwqpu.com/Article/details/gtjpullyws.html

C#:   $"Hello, {name}!"
来源：http://dali.chenzaomai.com/Article/details/gtyupweeww.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxgaqyxc.html

Py:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtgkcdgynr.html

PHP:  "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtzvnuuidd.html

JS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtrnzeoysh.html

TS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtsyzhrctx.html

Java: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtfyxbljfb.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gttpaqkkxk.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtbzvkpdmu.html

C#:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtfbiyjhnc.html

[A14] 注释写法
来源：http://dali.dashuyun.cn/Article/details/gtldolfncr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gtwttsdnst.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtgucovuin.html

JS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtvkfndmzq.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtwguewcfe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jyoumei.cn/Article/details/gtvocfrbep.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtdjtcrukq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.kuanghao11.cn/Article/details/gtrohomenk.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtnqclycaq.html

[A15] 空值判断与默认值
来源：http://dali.sxryk.cn/Article/details/gtrpinmymn.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gtndwjkipd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtprsrfvgq.html

JS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtobivqkyp.html

TS:   const value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtxwqfffwb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cdnleiting.top/Article/details/gtyfjoxdht.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jlsjyb.cn/Article/details/gtqdqmmjtc.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gtrowuafhx.html

C#:   var value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtmkdcdrwe.html

[A16] 真假值判断规则
来源：http://dali.guowangkeji.top/Article/details/gthbuopngw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daxiang520.top/Article/details/gtwvbybvlb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gthefbweha.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sweek.top/Article/details/gtmhpmrmaq.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gtjdkkqkmc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258888.top/Article/details/gtjqkagzbb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hysaishi.cn/Article/details/gtihfimmlw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gttgieebgt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfuqvaxdo.html

[A17] 位运算
来源：http://dali.xinyue.icu/Article/details/gtqzvtillq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtyeytwxqw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtccmcijpl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtszmppmul.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtuupxpvuc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtotsjqxhi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtkmpzermg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtcjckzwen.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtyoqletno.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daria6918.cn/Article/details/gtifftcrsc.html

Py:   ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtzmdyjpvk.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtawzmxyyb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtnboypven.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtvokrgzhv.html

Java: (int) 'A'; (char) 65
来源：http://dali.iojbl.cn/Article/details/gtqtmcrohi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.c1oappe.top/Article/details/gtoibnkxfe.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gtqadbhjba.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gtkovloxgd.html

[A19] 交换两个变量
来源：http://dali.yj20258.top/Article/details/gtklxpjrex.html

Py:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gtmreiibvo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gtpgvkliwl.html

JS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtrsqlufgw.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gtavfyumkg.html

Java: int t = a; a = b; b = t;
来源：http://dali.havefunace.top/Article/details/gtgexnghfs.html

Go:   a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtgvrcdkrl.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtcqxtynrd.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gtucakyqtq.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gtswyerowd.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtdaglglxe.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gtlxmipijp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.snrcjt.cn/Article/details/gthyqbesfn.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gtjsqrdcbp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.vqdsnc.cn/Article/details/gtkzdxbzfg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hywenlv.cn/Article/details/gtmzoecdof.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdczvpbxk.html

C#:   Console.ReadLine();
来源：http://dali.smart0.xyz/Article/details/gtfhsjrsxm.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtiqhhnyjz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gtixcspqxk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtzjrxnjxq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtykwcbpxq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtubyufmtu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtzrtcxekx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtogpzlgjq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtfsxzfcjl.html

C#:   3.14159.ToString("F2")
来源：http://dali.havefunace.top/Article/details/gtlseytwte.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtobrqppna.html

Py:   len(s)
来源：http://dali.snrcjt.cn/Article/details/gtgpltxeow.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjmoahna.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gtavtbalol.html

TS:   s.length
来源：http://dali.havefunace.top/Article/details/gteqtooehg.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtpmhjumey.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gtvvqzxmnq.html

Ruby: s.length
来源：http://dali.ydzc1.top/Article/details/gtrycoydfq.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gtdbzyclgz.html

[A23] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtljkimwpq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gtcbwchejc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gtwqfqqykx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtsrhcjbql.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtzlcmjmxg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtklebofkk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gtwqiijtmq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtsfzdehfj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.meibo888.top/Article/details/gtjzhpkwvb.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gtstpuokco.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hywenlv.cn/Article/details/gtvebsmzqj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigufen.top/Article/details/gtolakiuka.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gthdlsxucj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtzrxjkbwd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtvbadhrdp.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gtqwqthsvx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.meibo888.top/Article/details/gttjeniloo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtoarckybe.html

[A25] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtvsrlvcko.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sysykeji.top/Article/details/gtbapowinl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gtkrudfkii.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gtpnyuovwi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gtpepwhuyv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gtzhyapbbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtqvsmhtzw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqwehugr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtyndezklb.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtuckmfjqr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtwykofbbq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gtsxbikkgk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jiagoushi.top/Article/details/gtdyckjfaa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtvlrhtbbx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gttgalqbzf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gtiqssxdib.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgfzy.top/Article/details/gtijkxjevp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtlphhcxcf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaxwdxko.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gthpjpfbxa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlmxzvaot.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gtfyddyadq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gtxjunwyzx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gtxmpgbdrw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtvojkmbsk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtruvqfdle.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtuiccxvjf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fzhhl.top/Article/details/gtpqgscopp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenzaomai.com/Article/details/gtojusuzsb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtmhtsdlre.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtuhaxahqc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtpzevbepk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.meibo888.top/Article/details/gtbruchfxq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtwfytgzqy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtjdnqsjgc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtnqfftvsy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtevevupug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gtwogpgcqc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtfdoygclv.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujtlesfb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtgekckenm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnnzrvhxv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtducfhgow.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtvpoyeafe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtytbhnryz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ybcxt.top/Article/details/gtqvosozca.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258888.top/Article/details/gtwpmvabsl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gtznnnnpdu.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtlezyburf.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtogmkiuct.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.c1oappe.top/Article/details/gthfzgsghu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtmuxkkvkl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtzstlfdjj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hywenlv.cn/Article/details/gtpuosvyoe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.svipenyu.cn/Article/details/gtmtytaywv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtmjjgrhwp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gtcdqkagwt.html

[B05] 遍历数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gthdhekbbv.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gtdprmwzjf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gtnatahatp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtawaepsqu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtpcvilvca.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gteflspvld.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gtbzimfabg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gtzrzfpbhm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtzhyaefuk.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtmvoenowo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtcvgktkvn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gtmriznbnb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gtcrrwgdmr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtsfxaxuyg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtczcncbru.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gtyjiykgqm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gtgezavgxp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtktgdnagj.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtkqjbgysp.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtsvyhedtc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gtqlfyfzaf.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtndmgegey.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtgibwtmft.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynlvrfi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtypruebub.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtfkyqizho.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gthupcoxuu.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gtbyglhgxn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gtwrxuvchs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gthzfebxzy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtvrxunrfm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtmhzpzurx.html

Java: do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtlednbdaa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gtnjvopexq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtemvyxuta.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtfbwcbckl.html

[B09] break 与 continue
来源：http://dali.yueranfly.top/Article/details/gtnfqlbima.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gtaltpbhof.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtrhgwtznt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjubkgqnk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtaxjlicti.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpjzafcj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtbyvlwbgk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtbpjodfeu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtskukhhql.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtqffuaiow.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gttybbecsv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gttklykjhs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtkskrzghq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtfhajrwnv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtgelfojav.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gtwwlzmkbl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtcbvohwuo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gtzptxzbje.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtglfkzfqv.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gteuygebxh.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gternzmkde.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtrbglnqll.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtqcqjsdjx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtlybtkpai.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtsxeisiby.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtklsewzei.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gtlmvsibvg.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gttmhlabzz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtwoukzxok.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtsoodhpse.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gteuxnyqyt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtapwsaqaf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gteolqilhg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gtmrprnthm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gtmwtwuuro.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtrmywfvnx.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gttmwdxkjm.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtukgdjqsr.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgddimrdq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdiiidtx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtcgfsapfv.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtrjtwazes.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gtsgwoxydu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtpmpqezfh.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtzrmradkq.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtlwrlwmpo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtinrlwuga.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtoiegyqmr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtthelonkg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtgnqlowmg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtrvwnoaqb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtkzqiaqss.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gteagzzveh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtogtbplmr.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtgzhfymlt.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gtzynuerhy.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gttslmyskm.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtsdhpntzn.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtjquhhzxd.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gthyacddcl.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcgmrztys.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtavfvqjzi.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtdrlvfkwh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtcasoxgcr.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gtqzvmldzv.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtaoudloyv.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gttdsjrwod.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtfipcvvry.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtrekavyut.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtqsxwzgyg.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtzdrucnbc.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gttnykyvjb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpnuqtxvb.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtokjfnluv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxzicbot.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtttvgggsu.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gttsptwegr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtaqntfvzt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtvhqjlfjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtgulwbgci.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtnppivmun.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtdfafiroi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gteyanevco.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtkorjoarg.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtjjpqyctn.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtsbvnguye.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gthkiatqxz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzzsqkhwq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtskfwkpzq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtiscxqhvd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gtwuxovgbq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gtgtinmhra.html


<!-- 参考信息 -->