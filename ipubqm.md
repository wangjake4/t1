代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gtnsqpssmt.html

JS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gteempvcsr.html

TS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtfwvjkbwm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxinkj.top/Article/details/gtpwdcgoif.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.redwolf501.top/Article/details/gtwjvnjsps.html

Ruby: "Hello, #{name}!"
来源：http://dali.tian-w.cn/Article/details/gtikgddbut.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjanqxlwe.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gtcmkyyruu.html

Py:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtifltswbp.html

PHP:  "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtgiwohydr.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtohlhobwr.html

TS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtfzdppyyg.html

Java: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtxnrtewtr.html

Go:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtzmoyyrhg.html

Ruby: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gthybgcaph.html

C#:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtjqfijcrv.html

[A14] 注释写法
来源：http://dali.meibo888.top/Article/details/gtxcisrwsm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cucudq.cn/Article/details/gtxqnqcpsl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtlfgtcrte.html

JS:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtahaluura.html

TS:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gtgmyoadiv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zycfv.cn/Article/details/gtcwlbkvwi.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtuewxyuau.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.andypj.xyz/Article/details/gtirvmxbhp.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulhhhkug.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gtiysajrzs.html

Py:   value = data or "默认值"
来源：http://dali.gzhubu.top/Article/details/gtnmffrinn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtdalqzujl.html

JS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtfjbjpxoq.html

TS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtsmrlvoxk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gttimaxfuc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gogol.net.cn/Article/details/gttbqqgbwj.html

Ruby: value = data || "默认值"
来源：http://dali.snrcjt.cn/Article/details/gtlozhwyhf.html

C#:   var value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtlvnrsbfl.html

[A16] 真假值判断规则
来源：http://dali.guowangkeji.top/Article/details/gtqletwquw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.snrcjt.cn/Article/details/gtvqrmobqp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gtbkvapsen.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gtikqkvsep.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtjazalylg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xziqi.cn/Article/details/gtmszvevln.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sweek.top/Article/details/gtaygwpjhz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtfdumzbci.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.c1oappe.top/Article/details/gtyxfvqoum.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gtoqimujvv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gthgmifqxf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aizwys.cn/Article/details/gtmfnspfei.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtlmjvmyxx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gthnzvjoff.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtounkcnua.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtbsvvbjzd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtgsgyhllw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtjmcewwtf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.meibo888.top/Article/details/gtpzteeobi.html

Py:   ord("A"); chr(65)
来源：http://dali.cashguo.top/Article/details/gtebwctgtz.html

PHP:  ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtwamsmhvd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gtradcbxcl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtcinnlxlc.html

Java: (int) 'A'; (char) 65
来源：http://dali.wangdashe.top/Article/details/gtejscsumr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xinyue.icu/Article/details/gtuxlwmshh.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhongyouzk.top/Article/details/gtlaercvpp.html

C#:   (int)'A'; (char)65
来源：http://dali.0kj1m.cn/Article/details/gtnfpanijm.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gtoqeywhye.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gttxezdoyv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gtlccwoyel.html

JS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyehstbf.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtvdqaqiqg.html

Java: int t = a; a = b; b = t;
来源：http://dali.cdnleiting.top/Article/details/gtjkcwttxg.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtkiyxniqc.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtsshgsjjx.html

C#:   (a, b) = (b, a);
来源：http://dali.daria6918.cn/Article/details/gtqadukhtj.html

[A20] 读取标准输入
来源：http://dali.svipenyu.cn/Article/details/gtyfoentfy.html

Py:   name = input("请输入：")
来源：http://dali.yonumen.top/Article/details/gtdsfljtpv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrnyyhxo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.bjfxy.top/Article/details/gtdduknqoy.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigfzy.top/Article/details/gtejaeapdp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gtsgvajawo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gtqtqiegeg.html

Ruby: gets.chomp
来源：http://dali.gaohongyu789.top/Article/details/gtejorgnus.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtimmnabyz.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gtyrlczxyx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrprwamjh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtkvigzeoa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtxizfpbdk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gthvwxskfs.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtrfzcbvdp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtnnkdjdzc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtwgboggfz.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gtaglfpgad.html

[A22] 获取字符串长度
来源：http://dali.yongpay.top/Article/details/gtsjxzogzm.html

Py:   len(s)
来源：http://dali.havefunace.top/Article/details/gtxzoagsjv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aizwys.cn/Article/details/gtjoxnbxuk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhongyouzk.top/Article/details/gtorogvdrm.html

TS:   s.length
来源：http://dali.birdmap.top/Article/details/gtretgwjgu.html

Java: s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtgfowqzpv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cheryme.top/Article/details/gtgpngtgmi.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gtdfapahdq.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gtylvujyke.html

[A23] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtdcsnogxq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtlpzrmdnm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gtsxlxdgad.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtkrmbdnad.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtlglznfdw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtqmbwpzyk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.snrcjt.cn/Article/details/gtefkgzzkq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtszjshuis.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ppjwa.cn/Article/details/gtusskaeum.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtzjaqsmet.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.wangdashe.top/Article/details/gtlocukmos.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtwdhvtoaw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gthxjsnsha.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gttlbstjtm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigfzy.top/Article/details/gtcuciynfm.html

Go:   strings.TrimSpace(s)
来源：http://dali.9152youxi.cn/Article/details/gtssycakkl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.c1oappe.top/Article/details/gtojrzwtyt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gzhubu.top/Article/details/gtphycrlls.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtztgzecfg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gtaqhkgmbg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gtpohlnegk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtmqrhgcfg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxonjkimg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yvedp.cn/Article/details/gtlzyruqpi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtxxsblemk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gttoxbvdun.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gttuingpxl.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gtchfqrxwg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gtigmablwp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gtfkhrsedt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jyoumei.cn/Article/details/gtdoyqygff.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gtuojrpyvr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxrpzevr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hfpthk.cn/Article/details/gtoomyeeeb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.haohaochexian.top/Article/details/gtqstaxpmj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtwfnztawi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthxeolvvj.html

B. 流程控制
来源：http://dali.cucudq.cn/Article/details/gtlsihwqmk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfwvcqwas.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtxgtcpmuo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gtkbmuyudp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gtjqgpfgdm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtscwzbhpt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gteyhmhghz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gthmxitidv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gtwgunoxgt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gtgkzhbhoq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtchpxpyoz.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftlqavhh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gthygxtyip.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gtkkoqrkpm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtsxzqiktf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtnwsqnlvn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtukukgjjy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtklzsbfpj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gtgxedebez.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtyudbjlzc.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gtmtschwsj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtgvekkwrh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtyjcerlej.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtdhjxfjsu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtgqetutte.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphyfynjg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cqqwz.cn/Article/details/gttnprkhal.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gtnaxdrsgn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtzoovhwlo.html

[B04] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtbtvddjwt.html

Py:   for i in range(10): print(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdxgkfid.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtymjdiowu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdcimnai.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtgekcftgw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyymxxhdq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gotoacloud.top/Article/details/gtzqytbywg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gtrjqidaqz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gtbzipmtfk.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtbliyomwa.html

Py:   for item in arr: print(item)
来源：http://dali.andypj.xyz/Article/details/gtbyaxtdqf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gtwuqilrfh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtejcydhtj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtjissashv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gtzpwqdfnm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtbigzymva.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtbzdiiccj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gtpbhnwupz.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtysswayoi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gttztxqnhq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfzbuqad.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtaiulfcoc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtkuumfrag.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gtfdnkulxn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuanzhike.top/Article/details/gtukdtvmge.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gtrvvwtxby.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtsfghlnrt.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gtchwexycg.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtffcmkirq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gtaurhmoxt.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gttepejluv.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtaycmwpej.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtrcbllntj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gtcuhpomzl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gtyzctcdij.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtkdwrpuql.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtsqyudigy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtyddqxryq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtixxfjqqo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gttbpbbqif.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtkzbgktrf.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtlferknwa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtntiztdqd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gthcrrrsrj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtyncesvcb.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gtippbkdsh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtfvycmnqj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtcftwoqry.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtmqmwhwgt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtriusyfgc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gthgosuccw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmnwvpof.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gtrtlplygo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtigygnnjx.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtfmftegnh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtxpfergrk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtpagdozcl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtydpuwdeb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtycgsvcnr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jlsjyb.cn/Article/details/gtmfpzmsio.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtokdzjshd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtjhftsbye.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtcttlkkza.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtqgfhotlw.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtuljgucqu.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtkzcrijjr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtqgjatkjd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtnpqrjtah.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gtemzehhgn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtgkocewrj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoohtbtuh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzunrcokf.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gthkhrsuzu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtbrhtxnnj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtwzapbmxx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtafsqfgbm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtqirkqtml.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtcmdkhkdg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtuqzmxmmm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gttwjhoynr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gtmayygpnn.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwawkuqj.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtnqkqcarw.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiadmnokb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtnkqhidxr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtxguvjiba.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtnqcebhpi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtqvhhpghk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtxglbshfs.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtqbtgargv.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gtijkrpwjv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtvzcdxmpk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtpyfzeqeh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtowlbskhi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtvstheoiu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjvcexlz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtnbqavbrg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtgspxgwkr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtoebtkmtb.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gturnzqfog.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gtkpevesar.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtwwuhceaw.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtwiiqkyec.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtlxhvplkn.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtwrvzdorb.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhxcarng.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefsyaado.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtkphkjoez.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtzoyvsstg.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gttaxmsurx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtquqerstj.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtpymaivxg.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtfuasumal.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtuadxxwqk.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtgvaamdem.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtkkuvejbe.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtpotjvlqo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxdernui.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gthjcbntsc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttjrqtptf.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtlelcyokw.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtdgdzujbw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtyrxqyqii.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtbvbndvms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuxijgaew.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtzydvmnbt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtfkjcvyzi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtiilncddq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcnmaevht.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtjdbtkmys.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gttedbqfrn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtnhrfycjt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtlmunywfa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtwvolswoe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtmmaqjnxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gtgtdlaexc.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gthufhqpfq.html


<!-- 参考信息 -->