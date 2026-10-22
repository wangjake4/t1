代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cdnleiting.top/Article/details/gt2mqyfhicz.html

JS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2kwphcxnu.html

TS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gt2nlncwjdh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dianchejie.cn/Article/details/gt2keqdsqjs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ivvv.top/Article/details/gt2zcvwperu.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gt2ewktjvig.html

C#:   $"Hello, {name}!"
来源：http://dali.cheryme.top/Article/details/gt2ocvqjbwr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gt2zlwfndfu.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmwyqmta.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2xhdibyfb.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2llqspbwy.html

TS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2ykfsukrs.html

Java: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2vffxlscq.html

Go:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnwywkcz.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2ddyuqgyw.html

C#:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwsjxwqd.html

[A14] 注释写法
来源：http://dali.birdmap.top/Article/details/gt2kxqppxuw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaiyuraf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2xkgmhztb.html

JS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2djsfjhjf.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2fyajtxax.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cdnleiting.top/Article/details/gt2jdocbhjn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2smnfhpwu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fengsongda.top/Article/details/gt2kukrrcqf.html

C#:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2ejxuluil.html

[A15] 空值判断与默认值
来源：http://dali.yonumen.top/Article/details/gt2desrcrbk.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gt2dmkqedzl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfgsuuda.html

JS:   const value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gt2jlehlykt.html

TS:   const value = data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gt2nntjszmc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.aizwys.cn/Article/details/gt2zqrteljo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guowangkeji.top/Article/details/gt2kxdiamfw.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klgjqwhx.html

C#:   var value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gt2tlszwbgz.html

[A16] 真假值判断规则
来源：http://dali.tanke756.top/Article/details/gt2jfkmmvkn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gt2yakfddqh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gt2kppylatl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daxiang520.top/Article/details/gt2myxxkctn.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ymnxqkuj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhddbszn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbgurekc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gt2fkgzqftn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2haygkyum.html

[A17] 位运算
来源：http://dali.quarkkingdee.top/Article/details/gt2ldsiabrp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2jqgwzdop.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2rrvhznqg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2prmcosck.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emnlxjai.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2eqmqblig.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2uxmmgorv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2gtduugkn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2mxtmmfyx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gt2zzcxfnpx.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gt2oqhljjnu.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2meitxuxo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gt2dgaovbdu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2sdlecrgu.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gt2towlvrpq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gt2tjmmhzlh.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kndvvgmd.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2tebgnlwr.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcyivqvv.html

Py:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gt2rabgcbzd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yangfankeji.com/Article/details/gt2wzxmewzi.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gt2kdmgcpgy.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gt2dedkovoj.html

Java: int t = a; a = b; b = t;
来源：http://dali.jianghu66.top/Article/details/gt2gapwqhly.html

Go:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gt2sdsidipc.html

Ruby: a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gt2wlnkdges.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gt2lukpxmez.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gt2pjfqtxne.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gt2jwqlsyeo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yongpay.top/Article/details/gt2yjpcsyxh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.iojbl.cn/Article/details/gt2lhfcdnxy.html

TS:   // Node.js：readline 模块
来源：http://dali.tian-w.cn/Article/details/gt2drvytbfi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gotoacloud.top/Article/details/gt2rtglufxb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hfpthk.cn/Article/details/gt2tussuorz.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gt2pksiutkp.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gt2bvepwcoi.html

[A21] 保留指定小数位输出
来源：http://dali.gotoacloud.top/Article/details/gt2zzdedfpv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2batmrcwx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2yipdgcod.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2azihnmlk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czoaiawg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2ukgxcerh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2jnorsapy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gt2qrcbxzrl.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gt2mnurtagm.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2solryjxh.html

Py:   len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmdpidew.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenjidiqi.icu/Article/details/gt2elnwkgwd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gt2kghhhsqc.html

TS:   s.length
来源：http://dali.mhx1999.top/Article/details/gt2znuffmau.html

Java: s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2rnzcmrid.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gt2ckhcgbgy.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gt2ebkqtvta.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gt2pfumrzzz.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oezteeeq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2vmtruayr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gt2hwckkcno.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2makhdgzm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyxnqgmh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2pupjyxaq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gt2uuqfpknj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsjzuzrc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gt2axezagus.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjvbnr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gt2ecsolyur.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gt2tujcxbnk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxskdts.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyeaxdfw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gt2upyszxae.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gt2tmxkimyn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fengsongda.top/Article/details/gt2czcfyyes.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hanhyglx.html

[A25] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2vgqlnxrn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gt2cavmahns.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gotoacloud.top/Article/details/gt2hcadaebb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2edcmbdda.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2zqbpahas.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mctfrwfq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlrncybv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gt2aasuntbn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckopryzk.html

[A26] 类型转换总览
来源：http://dali.yanxiufei.cn/Article/details/gt2pusnchga.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2hifiguog.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gt2zlnpeayt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gt2nrfksouk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gt2yffhcrmj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2znbyeppb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tianlin.xyz/Article/details/gt2ntzwwefc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjjltanr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2nokhwwdu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2tflsaurx.html

B. 流程控制
来源：http://dali.cashguo.top/Article/details/gt2hmafbwtb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2njsaextm.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gt2xwoqsdus.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gt2duzbsmrg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hmmqdnhc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esfoxfrv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpkdlgsx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2dbzryidr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tian-w.cn/Article/details/gt2fbokjaot.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tian-w.cn/Article/details/gt2mukycmvs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2zneknifo.html

[B02] 多分支 else if / elif
来源：http://dali.fengsongda.top/Article/details/gt2trhoybrz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2kedpzrgw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gotoacloud.top/Article/details/gt2tdqargsn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gt2lxspmkdo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gt2zmuzgxhx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2ubyccsqe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzylwcls.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gt2znielmbe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcbdrfsq.html

[B03] switch / match / case
来源：http://dali.wangdashe.top/Article/details/gt2ukvjelmo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gt2uzlxsvcz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2lnzcihgr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2vcxdcwiz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2krjvldnv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2fyijpypb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2mfpweues.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gt2pntmdfxa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gt2zpztrwwg.html

[B04] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2tudjtrlb.html

Py:   for i in range(10): print(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2asiedtwr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gt2muurvojw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2csfhazbr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gt2kevqfihl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbtebivc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gt2zommatat.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxinkj.top/Article/details/gt2eceaggzf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tylpytyl.html

[B05] 遍历数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2ceaidvwh.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gt2qemyskre.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezfnwagj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epwvkxgn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2sdxomoze.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2hsqeknji.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gt2wnazjqei.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gt2oxxvbwbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2exgisjfe.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gt2togyyoud.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aavhxfkj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cmckijat.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2osciimsg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2owktktpl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gt2ijtehavy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gt2gsecgizg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gzhubu.top/Article/details/gt2wzqwytzw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gt2dmiwsbga.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gt2xyqoxlgs.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2uzjyqumd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gt2xmtfnwpf.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2ztzirobn.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2zgapqiov.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2ilcwkxcc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gt2zicdbaxw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gt2pttazvvo.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyxgiblb.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gt2krytbtjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaevakzu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2rjqpxalc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2scopouwf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyzhyhmk.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmykfjxu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjwluhwv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gt2jhnmlcxw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2lykvboyx.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gt2ryhyweym.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gt2kalhpwrn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xfdzjupb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2upalpjfv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rjimtbyd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2ataepuax.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gt2puwhynhh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gt2suyyumlz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2jtmgwynd.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgfwldzk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2vgwdwltq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gt2zbxuklbq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzpvjdtm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2uuxgsrqf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoqnezez.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gt2bayrpavj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gt2praqkuyf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xljwegjr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gt2jnfmfnrm.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipsgsrpe.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtebxyoz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjlndybw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2eguyzocl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gt2ixatyslp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gt2ikrwnsma.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gt2ehtmyosk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2uznwhpto.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gt2aozoyjyb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gt2fwazecwf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbcffvxh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2fiviarze.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2zxazoeju.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2pkgrgofi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gt2xvxryivx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gt2sdzxcoci.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2pomseuie.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gt2tvmthzwk.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwhhjpib.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gt2mauepccj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2mnagpwxt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2cdxzubcf.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gt2obtxldqf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gt2upnwskia.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gt2trefomsy.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gt2xgkppczx.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2yjiaaotx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2rixnbqjf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gt2nctdcits.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2zpoehing.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyzxfxcp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2kpfimqsy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gt2ssqpayei.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2jjlmlggs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2pzbkagif.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gt2cohshvrq.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gt2bpznyojg.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gt2qemsojqf.html

JS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2xleruzgh.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2cdsblxss.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2exsrzizw.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2oejemxwg.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2otwsjrzr.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2mcwhzsra.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2oaotpcua.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gt2eppqhtek.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gt2fsxyrtdm.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2deyyhhdd.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2kehyhoyt.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gt2bgpzxkjz.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gt2siudkjab.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2ysrhyhux.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2mutbxscz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2thqxinet.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gt2shwziynx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2glppslzw.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gt2tumrysjc.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gt2uaadnfdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xkxklmnb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2dbgvrfqv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwlvmxjt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2znpfgomo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2lpiukqli.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2xwncsgme.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2orulbald.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gt2ztilgcmu.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2lgpkpxpg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gt2usvijlyk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uiqpmcnp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2ggarvkwy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gt2bnpvhkcf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jynvtptq.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gt2mzvzirwp.html


<!-- 参考信息 -->