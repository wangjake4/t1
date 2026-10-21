代发 wailian999

[A14] 注释写法
来源：http://dali.tianlin.xyz/Article/details/gtfvacbeic.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yonumen.top/Article/details/gtytzjjynf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtinbzzkhm.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gtvchjneko.html

TS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpntserty.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigfzy.top/Article/details/gtshywywlj.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtkhynkmeh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hammf.cn/Article/details/gtqrjucdjt.html

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtulwrkefy.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gtmsshehjn.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gtfjbmwdma.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtqyyeqnud.html

JS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtvkoxjckr.html

TS:   const value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtmfmkfrvv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tianlin.xyz/Article/details/gtfqrhlqjq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aibaodan.cn/Article/details/gtenboxeyc.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtdqeapoaz.html

C#:   var value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtogzcvwoa.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtnzlvzrou.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuxming.cn/Article/details/gtoknkssgy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dianchejie.cn/Article/details/gtngbfaawb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gtmwryjrcf.html

TS:   if (!x) {}
来源：http://dali.redwolf501.top/Article/details/gtpxgdnacz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gtkacuhicv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtzyxdxuac.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nwbrower.top/Article/details/gtfwoymlit.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gtvazijouw.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gtbacbpgwg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtitzsympc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtheopfyfv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtadovcrka.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmesaogsz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtzhgmgjlm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtnchhahwc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtbfjyhtge.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjrwntau.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuxming.cn/Article/details/gtxvryzfuz.html

Py:   ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gteacporiy.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtwzeqbfcz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtmpzdalhc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtxajfahvm.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtfuuhlldz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gogol.net.cn/Article/details/gtkdiqelto.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczveureo.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtlqpktnrs.html

[A19] 交换两个变量
来源：http://dali.jiagoushi.top/Article/details/gtvivzbwsa.html

Py:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtrasxqxqy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xylfe.cn/Article/details/gtoyklgzud.html

JS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtwcankrlv.html

TS:   [a, b] = [b, a];
来源：http://dali.wangshuangyany.cn/Article/details/gtvgertjil.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gtlhrxmlsj.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtskqkwjca.html

Ruby: a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtcuqrqlaw.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtbwuweepy.html

[A20] 读取标准输入
来源：http://dali.ivvv.top/Article/details/gtazbcgqsg.html

Py:   name = input("请输入：")
来源：http://dali.hywenlv.cn/Article/details/gtzglgczat.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gttytndxrd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnfytsyn.html

TS:   // Node.js：readline 模块
来源：http://dali.daria6918.cn/Article/details/gthyfyhcox.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gtepjcnguz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hongshengwenyu.top/Article/details/gtymurtqey.html

Ruby: gets.chomp
来源：http://dali.ivvv.top/Article/details/gtmsuqmcww.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gtlxzlugvd.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtktpclord.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gtgonouwyi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtvpzaiipy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpifkdmja.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtdwrevjum.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtissbyqob.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtdprfkoiz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtswqtwerb.html

C#:   3.14159.ToString("F2")
来源：http://dali.quarkkingdee.top/Article/details/gtxzxiftwt.html

[A22] 获取字符串长度
来源：http://dali.sxryk.cn/Article/details/gtxdssaiox.html

Py:   len(s)
来源：http://dali.yueranfly.top/Article/details/gtvgicxvax.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.haohaochexian.top/Article/details/gttdotokjd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtbxqceiuj.html

TS:   s.length
来源：http://dali.yuanzhike.top/Article/details/gtirwdtvbb.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtsntidkpa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.redwolf501.top/Article/details/gtnsczhmfx.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gtgycieqlj.html

C#:   s.Length
来源：http://dali.ivvv.top/Article/details/gtrcqwwgrn.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtitxamqpo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnqaddlh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gtkjvtdequ.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtnavtjolx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtrgtibidy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtrqsunatw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gtngkwebey.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtmvcygtov.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gtqqlthjvi.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gtcxebykeu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtljynmmvv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhengqikj.top/Article/details/gtsujwbjee.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtzingkcjw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gttnpviwnr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gzhubu.top/Article/details/gtsmphrumb.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gtypzplvhe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shzxlz.cn/Article/details/gtasurekpw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtxsoagzut.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtfxszjdbe.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gtdffvawog.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtbwqtvgxc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtzhjysotu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtwcevhmuy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gtlnryhcgi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtrjowbkev.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gtzesimznj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtqrclnyli.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gtwsrnjadk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gzhubu.top/Article/details/gtdzrsgzfu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gtujqvztlx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtlqpuuyvf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ehwqpu.com/Article/details/gtkpvlfqql.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gttasqdvje.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gtkhopnpop.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtsrmtyowz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gtnclueqhi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjqyqbzjn.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gtcecjrbab.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthoajacrk.html

[B01] 条件判断 if / else
来源：http://dali.wangdashe.top/Article/details/gtkicosqsr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sysykeji.top/Article/details/gteovmufwy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhongyouzk.top/Article/details/gttldmqokw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtcdmdealy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtqwojvlgy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtutgjivln.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gtpaiciekg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xylfe.cn/Article/details/gtfiddmzkk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtxillqoea.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtzdozmxma.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gtfqydapnm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sxryk.cn/Article/details/gtwkvbsbgr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtyuivoivk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gteczcguzm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtykmlsoga.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtzjuxfciw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gtmnitcgsz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gteakfzhww.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkjgcvkg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtntvmrmnv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjivopxaz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtqhuduvti.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtbqfuwpcx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtawjapczt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtbntdythm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gtmvxbdsss.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtfsrjmqdp.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnixjeeyu.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtyzgzyjpo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tianlin.xyz/Article/details/gtwbndumgy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtldubiepi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfiypkij.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gtdyeslkqx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gturdfupea.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtdqjlgzch.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gtxnqoijau.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimtqhnbv.html

Py:   for item in arr: print(item)
来源：http://dali.zhengqikj.top/Article/details/gtfdwnffpd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrktlcrof.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtecqbskin.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtdsyrbqtv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjputyref.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhoulong.xyz/Article/details/gtpjmiooxl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pengpengdd.cyou/Article/details/gtxtekxsvu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gtptazlleh.html

[B06] 遍历字典 / 对象
来源：http://dali.kuanghao11.cn/Article/details/gtlksariby.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gtdeptwvgb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtdyroadeh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtiflmuxnw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gttrccedsu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxoxjubak.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gthbffyakw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtwrwphcwd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtakueuutz.html

[B07] while 循环
来源：http://dali.smart0.xyz/Article/details/gtkyerbakc.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gtokdapjsx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtpyjqmsgh.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtzmawfnck.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtibhrmtke.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtkyspifwm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqhcujyq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulbkxokf.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtcbpwquek.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtvjlazqlj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtmhoasxcl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtgbwxudkp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtzfdhhmwb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtgjyzbjsu.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtdazonwxt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gtsktgdkam.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtyyoturrb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtmkfbgghh.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtjheopenq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhixingplan.top/Article/details/gtubjxdwya.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtweokfybb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtymixysro.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtrtptspnp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gthetegmrw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtgkrdphbu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtxyjxoxsi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtyaaagdoe.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtbxqonquk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gtfyyigdfz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqlbdqjqa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gtintrjiiv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtmolgovuj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtcvbgchrn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtkvseuamu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tianlin.xyz/Article/details/gtmuozmwdm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtnikioooe.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtehygtvcy.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtlgwyohaa.html

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gtlscqxemh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtswdmiswj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtlgxuktoi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gthtzgmjhd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtlfygykml.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtevcgoxbp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtqbnreocv.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtswgyzlhx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtbvgogkjp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gtfjkhrjsd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtqpmwamzw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtoaxvblqm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjsdyqduh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtuvvezhsb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtwgiahyws.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtsorhvvss.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtanqmybsx.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtugkqvkwc.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmbjofhy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtrifyjeae.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtyyytxyll.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgcbkfvx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtlmfvigqr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtdgbzgkxl.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gtkxrnitar.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtrlkxdqxe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtncqkbddg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqlstoqe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtzreckmiy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtdxknfkbc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtuqvkkhhn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gtngnilfzo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtouvvqupd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtxnvyxphq.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gthlyuiufy.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtfjrzxegn.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gthbgpqvpb.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtnjbpzyvv.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtpezsntpi.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtmfoypnzx.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gthijwtreu.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtlihrexqo.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtbufkcdkj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtymevmvtg.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtfcuogukb.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtdkxlvsln.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtvpesaybn.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtrsctguky.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtwsbpzrzi.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtdmstcjbr.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtruhzhxee.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtytwnwqzi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttprzjdwc.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtsrwpmxwn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfsfioumn.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtusbhbuvd.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtvqqkpipg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtwskisrlg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtoekwtrqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtnwdjtvkk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtvazmuqvq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gticbpavvy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqupjspt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaisfhdy.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtkvdpptml.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtyvjrcaua.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtvnbghmwk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpixgipak.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtfdlgaahd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gtzzgwfczu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gteppvfwmd.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtjhopcayj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtreaxtqdr.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnosfuvwd.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtzygplcfp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtgkppycre.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtmhaqcyvu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtdgbpeqdx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtkqssxxth.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtlbucejwe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gttqpjkuwh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gtkamyarlz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sufxvd.cn/Article/details/gtcglaufwq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtonmmljab.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtxfgtamzb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtbbjwhdcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtrmnrpdtb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gtlwtsoito.html


<!-- 参考信息 -->