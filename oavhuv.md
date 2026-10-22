代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2lubgccxm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2mttaqiuf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rebyjsic.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2csbkxatz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqvatjue.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufdfjsij.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2nnhjrzvp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2fqbkrjsq.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gt2baigrtnr.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2wctamncz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2ytgsnjlo.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2mtuqhrhq.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpxtyqaz.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2ntkeoafi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2lbtywrcf.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2ocwimrse.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2clfmbkmt.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdaruqfr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gt2ecziqick.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2czjiapom.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbbfumvx.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2thjdsmfn.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2pflqxatr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2chgbghuu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2wkidfejz.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gt2dolbupnt.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gt2tubxhcdl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2hzlgaiiz.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaaynfpw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2loiaulas.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2kwhujawp.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rklysddr.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gt2duqtawoq.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2xcdyspwt.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2epxzaeyz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2npcralkd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2wpfryfbz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gt2mbeffviv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2cegdjyak.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2esfagvog.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfxrcfzh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gt2yoczvewg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gt2phwrcsqr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2gfexuzfd.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2kskkwwpb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2nnxjitue.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2ixetjzqd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2jlsteasl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2evgciahm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2tadlcpub.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2weogdpix.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2ilikqsrj.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2gckouodz.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2odpnmrxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gt2reasrcak.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laywyacv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2edrzjyoc.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gt2olwmbxnd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gt2hmawmurf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwsrlfmv.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2dqfivxja.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2dqgldzoq.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2flvgdpff.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gt2pnwjrbzi.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfrilsbf.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2qgclgobs.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2koudvclt.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2danwwsqc.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gt2xbiektli.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2hgdduxqv.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2tdbbuvfb.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gt2qhpdjxoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2qjbvuxyi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2sakjvhrc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2dnqmffgh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfgzrabp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2npioqiix.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gt2lnaqfkem.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gt2gfjvsjcm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sywmwvqk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkqwiihl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2hjbixuhs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2jimzxrwg.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2xyyxtbyf.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2hyiknlfb.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2bsmidaub.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2yoiclstm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2xhbuzywo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqygvgqc.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2vvpxgtdx.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2nvalwxea.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2krwivhps.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2quggepop.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2pkggtsgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2mitovacw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2dsgquxig.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2diuvhmhq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2xtqnkavt.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2hzikhwtl.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2lxmwwaew.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gt2tfobfusa.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2txcxknab.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zznknmvz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2jqcyjtca.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2dsgglutq.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2enbmlrtu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gt2frhiznfs.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2pexershl.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2tbeojwti.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2fkpimevv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2djhlgutb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2qzesmpwm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2adtmuank.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2rhfzyyly.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2coctmoql.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2atstbksw.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gt2iuoxhhob.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2rbgkbigq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2qjnvtfrb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gt2cvvbuolz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2ujiizbsn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2upsygvnc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gt2kwyzuvje.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwyypoik.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2hueooykx.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gt2jacqmili.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ihsjeusk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2tjyqeyuf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emuawmil.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gt2xcqngpmr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gt2lihphdec.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hisivduz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gt2nbyqrsme.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gogbyfpi.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gt2sxsdetbi.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2omkgrrgc.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2zvynchen.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2wneebqgj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2bnziwsva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2lbdsokns.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gt2zvxrmxyn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2gzummxtk.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gt2nyuduaxz.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2iqqddctk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gt2xueeylix.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdvbftgb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmoivgmy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2harhxsbq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2mlftayxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gt2nrebqfqy.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2bhvunuvg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmngeu.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2arqovzad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2kfcoxoog.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gt2akxjarzh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2xowhvxou.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eicaioqa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2tyhvnpxd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2kuemhtvd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erkxwvgq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gt2iqculisj.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2vmyznjao.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gt2dvkwgmwx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2prittcjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovrhuqas.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itpbcrvu.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gt2lpqjedep.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2fctnckoi.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwmnexds.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gt2tawrtxdx.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2vfdprwey.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jivaluqt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2dfahfarr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gicuqyvn.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jrokievg.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2iqjkfren.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2mtlqcneb.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2actiwoqk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2wvrdjltf.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2lhpuhrjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojopqptk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2wzcdrvaw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2ephvhnoa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2bgerafkd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2uwrcwexf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2ydidrzmy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieaqihzs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2fxpmrbpe.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2rcqtjszf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2naqpownw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2weqkdyul.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2vjuvyfjg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2vtbzyebj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2bdjqppjb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2atlhpsjz.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2ibbnhgvj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2venbhfbx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2gnomldfc.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2bgdqvexl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2nbxoqkiu.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysprofyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gt2owuouojj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2vslrogdb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2nlsbicff.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2nuneylfh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2srywyfkh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gt2hhtqkpnp.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2drggybht.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2yvvfqojd.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2skmlpeez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2vxgdxyty.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yvqefnuu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2njhtndcu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rjdoitwj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2twyyyuim.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2xbcjnush.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gt2ovfhshhj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gt2mdmzrwyt.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ritvuoaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2jrtbjzsd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2nyxrqtwo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wunvuylx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2fxpctela.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2jqwkexmu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxsjmwei.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gt2tkghxekk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzgkhlyp.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2rgrzkbsf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eookzass.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqiphonr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2hujnslqn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ashvmwgv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2tkamvsnh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2ylmpktas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2gqdwzfdb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2aizmezqc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2brroqbjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2mosumddk.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2caepypya.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvwacjix.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wokuptay.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2ecsuhzoc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhtfvvkt.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2pnxnuonl.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qxkkwkqe.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2lsrohhen.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jgytbgqz.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhyfgdld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2xayqvzoj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2fmtbbfis.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2rtaxyzfe.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2rmzgelwv.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnucmdrs.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2tzmlgcqn.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckehcddi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2azjukuox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2rxcfiuyo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2hyzibmpf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2mlsmhwsg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2oazacghd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2hzlqbjht.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2klxuwiur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2cjrwcfkl.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2lgwandwi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2sswmmofl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2lsjkjpbs.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2vwunwdyx.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2gjeiljhj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2sdmjhmjn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2qjqoajud.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2attqoois.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2bankadsy.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmxltmyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nxtyykni.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2yrckoxfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2qkdieucg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2nhlqtlym.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2laiesfyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2txxhbpeu.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2svmsnjel.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2ckyxshwe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gt2rybgidfu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkgzzkyp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2ccflwlch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2knvhebxl.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2adyswrel.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2lzyoaboo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2pziqceiw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2jysukfrb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2mbcdafhf.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2aymzmdfd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2tvtokdur.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2zqdzjhzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2bcxojqmb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2oehltgio.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkgdmqau.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2kzjqwtqc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrhyrjtb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2baokkxou.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2jqpbjrez.html


<!-- 参考信息 -->