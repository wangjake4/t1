代发 wailian999

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdramwauz.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtrnyojhle.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtoemxntoh.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtkbwotgfd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gtwpzutlhc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtxtevlwbh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyotplwde.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtaiaulzcs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gthzoqcyhc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtvsibcfhs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtxshdzlki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtfzviwekx.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtutpwyrrv.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtevbgysmy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtfdxkkkhj.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtadrhkfbm.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtbtxdafra.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtngyjuqcu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfajieeh.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtzemtglpe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtysnkrsgc.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtfamamkbd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtgxnqmoxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtjuoapcup.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtskrvokfc.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gteczbcjnb.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtekhgoibh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gthfkrqnuq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtmkbtmrqf.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtxgricixx.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtrwlcatql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlcvandl.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtfwhggaev.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfgolymw.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtextepdcv.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gttwyaxfgu.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttreguwxv.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtomacszrg.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtvvqnafau.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtchgijvfs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtvnjtflfg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtyypvonxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtwjyvirfy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtcvttcegq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtdmsaxnsc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtfporleli.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtkgbhlxxz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtgyihfiop.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gthtkgcoqt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gteddxnjfn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtkvdlglxi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtngmnfhih.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtejnfdbje.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gttkhazkbp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtesluhsxv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtzswssbqe.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtopezrmmn.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtmllwbfvx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtqcdarjap.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtocvzppsp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtofqjustl.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtjziutlbx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtgvfuvgpf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgywvthx.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtqablypqg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtnhgshvbi.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gtnybehuwh.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtnzeyyfae.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtyoywzrlz.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtbbgrpfaq.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqthibcii.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtewevgpmj.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtcdxownwe.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtohujrway.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtuzkzycas.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtgphlevbd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtvaqfpwxu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtrquuusji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gthcvfegjw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtvgompxka.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtblaoekvb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtmkotbczo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtxoqbuhmp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtsovwhetg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtgqwnkvid.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafvpgiab.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtluzrtgrm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtzeuekndd.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtifzbbiut.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtawcgpgrv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gthzdhvtoa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtlywhkacv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtfjuwbmpw.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gthmvbeojf.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtrmmdsdha.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtnggrgmue.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhkdthtj.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtbwnhvcad.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtmzuaffcn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtzlhkahai.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtfvvdqayp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gteoxrtsah.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhjrlhjf.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtweyhvkio.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwnmxnte.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtccgaopzk.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtpfcmlcuk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtxhpnnkqy.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtrzuxhyoe.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtjzyioxwo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtrdfwqysh.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtitfksgfj.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtovbgkmpo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtuxqrpnhn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtkafrblgj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtidltfatq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtlgsftejj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtohxmpjmb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtunfatkfg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtgqqylepe.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtkqoteqjm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtsnsagduc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtzpbtphta.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gtlizhiwik.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtqqukxqip.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtcpcbhkmd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtltnfphyi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtasosbfob.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtmxqlspwf.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtrlbzsizw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtntfbscyi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtncakjorl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtattdhdkt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtuysjsxvv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gttoxfslpg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtmbodpiqz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfekqahlo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtskqrqxfv.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtlnqhsopy.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtdyvzwmtu.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtvauphypq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtnyisieys.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtjxhwyfal.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gttixzfxre.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtffklaimk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtkgmndzuk.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtoyoigvag.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtelzsbjzr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtehyldnlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthsxucfnd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtztwqijwa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtihqfusws.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtoxinuutn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gtuaxtupmv.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtlkevlyyg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtfcsbeghc.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtncqkrply.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtczfcsgkr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtmxrjuvwq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtebjgwjiw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtkpyixfbh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzjibkyu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoenjelb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtjybakltj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtvefhvojl.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtryxjtijb.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtflauttbs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzrwfcmev.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtrltnywed.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtmjcbgwas.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtbjgcdqvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtejtaerci.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtuujcfnwo.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gtsyeohwzc.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtczqhqwbf.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtyziwzomr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtfetibqyv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoixpyvop.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtglblgrul.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtupazdube.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtimgkmzkt.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtjuonkbgq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtwyghfiuz.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtrugxuwjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtgoggnhty.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtuhrsxvqm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtitvakdub.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtbyqhltuh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtytwjqsym.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtcctidnez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtrkmlgnso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtxutvtdqz.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtgfdfnrsi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtobuygqfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbioskno.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gterbyvozd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gttbrpgcay.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtmlvdwivg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtgayhopnf.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtufvyqtxf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtybumcbbd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtscbvsblw.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtnzbetccl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxrlssuxb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtbzkqzgla.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtnyenbgoh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtacelljiz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gtzqnwlgnb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtevxxqtkn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtnryyfljj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtpzzvhgab.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqpznyiii.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtuzmflhjj.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtvmeqljac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtlzvdgssh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcameluwc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtgakzewdt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtssqfasbk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtkmcoiunt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtlvxvbyws.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtoblcgbto.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwktacinh.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtehmcgmbv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcblnxgtn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtsttdzffg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtmcpqfysn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtwaywpbsb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtyeglmdqv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtmuvteiba.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtboysqlgy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtslvnwmda.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtlrwbptlm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtpmjlkgdx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtirvazjyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtxqqfyllc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gthjrxlimo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtjbagdnsb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtyzpreqqw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtkynqdmiq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtjkbqrxlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gttyiegnwl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtzalpaknh.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvfzhpmxx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnjzwomdj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdrdhzejv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gttliwdvps.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtsdektmid.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpqsajati.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcvgklnyp.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtqzhzrqwa.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqydsmmiv.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtcxukeqnt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtoxmwykpz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtvqmsumgv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmqjaxfug.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbgzcwhdj.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwkubxijh.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtsliurruu.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtfmkdpoay.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtvfqrbtgm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtvkzdsrgs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gthyhapdsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtlvecejnd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtulhnmifx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtaztakldu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtdxsdildx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtraguxuud.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtrdniybfh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtdmkqbkfg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtqfnvgqak.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gterkrxmhg.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtbtnlwquc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gttnstmjpf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtmxwzlpjr.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtwxuprwmv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gttkhjuibf.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtiyegunol.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtjsmhpmnd.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtjmjpbadc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtkioczamh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtdcxabelg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtbaxgotlw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtrcqvskrc.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtelfqbfze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gtckefebaa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtrpkbjrng.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtntsmvejb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gturiymfiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtmvourlwq.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthmyklzni.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtdxzncvql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuifepixu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtelhuaamw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrdfnnhdk.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnokqvme.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqpmaykrv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtnoifnaet.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtskjksohx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhnsdpcw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtvmibpbro.html


<!-- 参考信息 -->