代发 wailian999

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuxming.cn/Article/details/gtwlztgnak.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtpncqolyb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gtycbzcngp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtdqcafele.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtwsdetmcu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dianchejie.cn/Article/details/gtfkhxvtih.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gthzisahbm.html

[A09] 绝对值与最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtaygcwoud.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtzjrstkng.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtglfqlebo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtveblxeyc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtxionobza.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtwqrfdums.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yonumen.top/Article/details/gtzvdpnxrg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gtzsiwpsxc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytvwrmbj.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gttdoyjexb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yongpay.top/Article/details/gtblwchapz.html

PHP:  random_int(1, 100);
来源：http://dali.yuxming.cn/Article/details/gtijfwyksd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gtmcyfnfws.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gtnqlvvfso.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtmuwhitsd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xuetiantiany.cn/Article/details/gtfuiwxvgh.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfxgtshy.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gtczwevbxu.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gtdlttnkvm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gtspltkasl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtgjxmzbdk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtxtvrzpje.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtvblydocd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtkunnzknp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhengqikj.top/Article/details/gtsioqtokj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtevikoidz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtfrkmsnal.html

[A12] 字符串插值 / 格式化
来源：http://dali.birdmap.top/Article/details/gtapqhredm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdydlyoir.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.snrcjt.cn/Article/details/gtheyhztwu.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gtazghxlvo.html

TS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gtzaunwkht.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gtlzncfyjh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fengsongda.top/Article/details/gtatiakvcc.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwzttkcd.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gtwdvuvjph.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ehwqpu.com/Article/details/gtbmvqogia.html

Py:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gthfdfkidk.html

PHP:  "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gthjstgfbo.html

JS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtswtfnznw.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtbklrrmeq.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtekwvdhcg.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtjeablunl.html

Ruby: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtdwvuotpv.html

C#:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gthvswwqyq.html

[A14] 注释写法
来源：http://dali.pycfn.com/Article/details/gtlnxxzccy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pycfn.com/Article/details/gtbxvdweko.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtmfdblsci.html

JS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtmftdausn.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtkzghifxf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tianlin.xyz/Article/details/gtdafsdfch.html

Go:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtjpcquwyh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sysykeji.top/Article/details/gtmhahwpqb.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtsdoppspl.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gtpufbzrfz.html

Py:   value = data or "默认值"
来源：http://dali.tian-w.cn/Article/details/gtoznmjkgq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtczdhuhqw.html

JS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtefbzwodj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovaqrktl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gtsmhnlwzj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.meibo888.top/Article/details/gtsgwzdfov.html

Ruby: value = data || "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqpizhte.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtuxjvqhhi.html

[A16] 真假值判断规则
来源：http://dali.hongshengwenyu.top/Article/details/gtuofisgeo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtpidraitf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gtubovlqks.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtzoqlzlpk.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gtylbmuvfy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfeysmgzf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nwbrower.top/Article/details/gtlbdyzfoi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yanxiufei.cn/Article/details/gthwyuhqkd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtlbjbttka.html

[A17] 位运算
来源：http://dali.ydzc1.top/Article/details/gtyukptbvh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtkuzclwii.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtotobchpl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtcfknadav.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtcuekxhil.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtiijifscy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gttoqekrqr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtuwufsghq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtxyojvspk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnxiangtu.top/Article/details/gtikxgeics.html

Py:   ord("A"); chr(65)
来源：http://dali.wangshuangyany.cn/Article/details/gteiruvsqs.html

PHP:  ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtggcyuajo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtlimbnzqv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspkmsdpq.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxuanxn.top/Article/details/gttrvymejo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtwaotanqg.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gtqcidzxct.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxinkj.top/Article/details/gtbscewmgz.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gtqipdsven.html

Py:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtrzudxujd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jqgufenzy.top/Article/details/gtokbhntyb.html

JS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gtokvtrrto.html

TS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gtjjgnrjbv.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhiwuduotai.top/Article/details/gtcwmdnyag.html

Go:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtynpeppmd.html

Ruby: a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gteoopvxdw.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gtaoxgooiy.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gtqkmrcimd.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gtmhhfdyfd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtexwvecyc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ehwqpu.com/Article/details/gtdxpwtmyt.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gtwijrjage.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gtyqeppczr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.meibo888.top/Article/details/gtxymnebqd.html

Ruby: gets.chomp
来源：http://dali.pycfn.com/Article/details/gtbgidrjuh.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtxonhwzrw.html

[A21] 保留指定小数位输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoccnhdb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zdqjudy.top/Article/details/gtxdmvqqzm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtddxsjjgc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtoxaawalo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtubponsmg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtpemuipsi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtiuzawlgw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtinawwbqy.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gtyetahxuk.html

[A22] 获取字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtpcsmdasm.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtszlrnjcx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj202588.top/Article/details/gtskllteoq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosdorrts.html

TS:   s.length
来源：http://dali.smart0.xyz/Article/details/gtfaaklkgs.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gtxsdpvbsx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gtgxtrmzax.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtpnawckuy.html

C#:   s.Length
来源：http://dali.fzhhl.top/Article/details/gtfshclrtu.html

[A23] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtnrskkzic.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtodzklbuf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhixingplan.top/Article/details/gtmembavvp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtfgdbjske.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtwkzxtbfe.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnpetyhk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtocufbygu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtzpvarjhx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gtgapdnnat.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gtvwchnuwh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yangfankeji.com/Article/details/gtumlhjyur.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gtpmrnkxqo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtcjrerhyw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmvhqmov.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gtxhahisvt.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtkwgcriiq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gtdlgirsev.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtsxnroxuj.html

[A25] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtgyzccthn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gtkylldwcr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gtimyltotn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gteshjsuku.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtocwvzqum.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtkmxltysy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtehrijoyz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ydzc1.top/Article/details/gtojybufqf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtyxgnzmmj.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gtoqxxvkoc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfvtkjcv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtghhzygko.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.iojbl.cn/Article/details/gtfnlyevua.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gthtfdrtjm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtxoubwslf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gtdjopklxr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtmezsopni.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcbshnri.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlypadpqk.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gtjcvdyagg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjymgvmyi.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gthhmueerm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtsucnnlxn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtfoqbeswc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtndxouyic.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtyrdrxapu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtozgwatrf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtjdhaqath.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cheryme.top/Article/details/gtjvvnimef.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtbranygho.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gtghpxmpuj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtpiaslyqm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gtmqlaowiw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtglvtvpvc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtjdcfsstv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtchwxcusf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gthycbpqxy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gtragovzja.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtglnvcwiq.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtybuadwnu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sxryk.cn/Article/details/gtnngcelnh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtqgiknjmz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtateomulz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtkslvajek.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgktkjklu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gtotoyokln.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtjxijiqpo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtbipgsban.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtacpgttaz.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtxgdlubgp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqnuwjhr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtjnyylhtp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtfewcrkgt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtipukfbkq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoudkrdmm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gtyiujdqrx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gtwyujgxua.html

[B05] 遍历数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtgjshffry.html

Py:   for item in arr: print(item)
来源：http://dali.gzhubu.top/Article/details/gttlhljkru.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtfelqbgmh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtvggkgfjl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gtodheszul.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gtptaicnps.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtrhlqqvdn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtztldedbj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtcadttevn.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtbmpguacx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aizwys.cn/Article/details/gteueohusl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtynaovwfg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtzqnhllrn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtdcotpvjv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuhbmwzv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.svipenyu.cn/Article/details/gthdymhhda.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbfxkswi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtxbjljitl.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtviszbulk.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gtxqjygnda.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtgvrlszre.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtcfiwqrpt.html

TS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gttwyalxgy.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtjvfdwcpb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gtunyycuzi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtzsabntye.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwdiqpixe.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gtomdotmhy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtuoozpjct.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtgjmgcwqf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtovafpspx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtqdpsoklz.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtvpqnxvzc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtclexwazj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gtifmfxbre.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtwzuamnev.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gtjfsijbto.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gthnjakjbb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtinbpxkog.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtfcvlshwb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtwtucqwtp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtlrkdnqzk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guowangkeji.top/Article/details/gtzziosjud.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gtjaypcykn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcovyziq.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtgixuakxo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpydfycw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtzrgwzbmn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtokdfgyly.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtmyyvprsm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwroeaaub.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gtrcmnlieh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtjhosesne.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gtsxcxorfb.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gttnhuowbd.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gtvzxfawlt.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtkcsdwixm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtuthnixnu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtjrcfaxen.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtbzsjsunl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtnunodfye.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gttzdbbogi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gtocmlueac.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtrnqarese.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gttinzwass.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gtzvcvclei.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtagvpdyuz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtlwuvipkl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtfkunepen.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pycfn.com/Article/details/gtaarlkimn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtnjqjfhke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gtvrvphqwb.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gtrakcpabm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtfwbcqqoc.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gtnwbmrvfg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gthabydrhi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtlwaxhjwy.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gttbaqrdzd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtawdtfflb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtclgfyjcq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtlvfqiuqk.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuknwfso.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gtzlmjnwak.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtjqznpmss.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtikzmpugr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsgpshbvz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gthicdaioj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gttolyfnya.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtrhgquevo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtrjmopcqk.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzcbtltd.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtqdlldeaw.html


<!-- 参考信息 -->