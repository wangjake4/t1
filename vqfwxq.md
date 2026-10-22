代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2azhnvfjg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2fzeysder.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2cjtsutua.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2lhshgymu.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2qhtsidxk.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2wnkictdu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2floocenp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2nsqhvghp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzsqgdvx.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gt2gbrcwzac.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2unzzxkxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2sgkbmlpu.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vneciiyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gt2rdahqmxt.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gt2icgbqcqm.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gt2fsciexpa.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gt2ivcwcztp.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2vtqutqcz.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2vqwnxocx.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2suepvslo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gt2sxjzfotf.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2ljbiqlsf.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2oavhkmny.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2avqarmmp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gt2eoaznkya.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2ltzzbsah.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aksejsyb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2vaimdakl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2potaplhl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gt2wrhbrlwc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2xatwtlrg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2fznwfzzz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2lfuiueaq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2zbteegly.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gt2etwxowzx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2redavohb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2mgjotvno.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srjthfmn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2xramlplt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2lzawvdjv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2vahiruje.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ztjtdjhr.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2tovgqhcv.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2efbvvqka.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmrsejon.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2sjtnpitg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2omrfddcr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2vvgemubu.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2bqksdxlu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2ijtfpgql.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2pckqmthd.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2kfbgccqs.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2cdxmgckn.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2etzkoeqs.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2deiyqrop.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2uzxwfjjl.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2hdvywzma.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2pljffogq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2heewydgt.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2uijxigyo.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2kckvbmaf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gt2hottumma.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2yhldnpwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dxrforjl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgpvzmlh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2zotueeqw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2gpcexfxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icdvpayx.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2cdabghpz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gt2svjnuvzu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gt2fmafqqez.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2pxpdoptn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gt2aaafaqwo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2xkgqiydv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gt2ctuutxbg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2rayaqyzt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2zwzvdmtl.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2cwcaktog.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gt2dkqayqhc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2ffsfqoqt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2xdaujbpr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2yiecjjan.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gt2bubwqums.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbykyilo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2hqtaqgrv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gt2hksblrqn.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2qekyxlvs.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2ksqhdlsg.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2ilhwpjqw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2hgkfdehw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2mopnuube.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2biirjlsb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2xjwzfmym.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbanihuu.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gt2uvpejzqs.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2akxnmxsw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2spstfgqs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gt2eddeoucv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2cfdehchp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2rrrjuzdl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ekszwznu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gt2vchmzuai.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2vftxbzhi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2ywvrthev.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjcprdlw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gt2ximozurv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvpymrci.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2ydtvwiro.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2bqhjibyf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2khrovjpo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2gjosryek.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdrkabs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gt2pnhifegb.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gt2vswwisxv.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gt2xvyualim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2wvhlrwir.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2dgjbtljz.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2tfrostnv.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hylivlqo.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gt2xbblkpbr.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gt2spzadtzi.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2lcxoskre.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gt2txaaanzl.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2cdplwkih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2qzqxjgqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2dagqwztt.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2uxkzyfhy.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lpwbzeiu.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnldndfy.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gt2wradsvju.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2oaxkmsxq.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtysxajl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2rzfwrrmb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2qaetrmii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2hylqudlo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2qaqtyvby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2bpzgdjiz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpdzalfa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2nhrjldki.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2sctrpufx.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gt2wuqfwhfq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2cqyojsxb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2bhmvicrh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2foqqquzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2gkjjdgnj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2vrxphvof.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gt2ayyicnin.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2wthighuj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2dtoyveqc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apbrtxsb.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gt2vhfxofct.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btujuhtd.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2dxgsnoxy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2pxmstrdy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2fjpdsehi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2niqayeza.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2ilhcxahl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2bgukxuqg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2yyxacxcz.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2fazttnha.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ubsjfqic.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2ylfbmawv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwqcabcy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yyoqdplk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2kpkljiwm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2lqoccsjj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2mhfzfbxp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2safoyigu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2xbaljazf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sozxyzlu.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2bbiyepro.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gt2kxmrjvsh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gt2wuylwnzm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2zwsfxpvq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2brbsaspv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2mmrwzepf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2tmkdovjo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gt2nctpspmh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2cjccmlow.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2lcfkxynp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2qzbqthpw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxpbatmk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2hcyduscb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2oiqxuypb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gt2jaoapcyq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2hsiucaxg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gt2fkxqpzia.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2rozfdard.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2pssfsnja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2zuzzjwuj.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2jjwkwxck.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ekcclugr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2bvekvmuk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2vutmwjpi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2jfxjaera.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gvdyvbjt.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ijcrbgfq.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2rkhrrlun.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2zuibvokd.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvrazviu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ijrjcwoc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2lxvesqaa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2zialazdd.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2mzsdjitj.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pbstpklk.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2sfmfjqbs.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2tfjbklhq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwaccacn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2wpmcvdap.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2cktrgvfk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2yqszdbrw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2lufbegcq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2hkinppse.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2dgszmjum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2mjnqqjvz.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjrvyxek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2ufiykkii.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2amqckmxe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2dijqwhdz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2etrbwpcs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2nsfxqosr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2rexsjhsl.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2jegwtrev.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2gwhsaavo.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2wxpdxkwv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gexyuqhl.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2sythmzvn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2npwurnfu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2lyhmuipw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2jmedptud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2yjmuhlqo.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkmzasjr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2zvvmsbwr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gt2kfcniukn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxjoxbsf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2wqfiggnu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2nbcvtnic.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2yblncsvt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2nlbhmnbl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejagcbhs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2drztzvwe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ncoxlfim.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2xrovbfca.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vjbgzrhn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2azpxheuq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2sbciewxi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ocxwedil.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2cfrjvozn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2beamfmvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2cvpviodz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2oninglkn.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhjisyie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gt2ywjrmdne.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2jutpcmuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gt2jpidmlfg.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2qgifredp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2agknqqpg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2ygqgjmql.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2cbqotolh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2rrzompzz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pysepvmn.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gt2pkqhnwri.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gsajwiva.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2cjpfnzrz.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2mvnidtmq.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2vxwcsrno.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2jmbgltih.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2jzeqfess.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bzurgwgd.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gt2ywwwzlkb.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2jsgrxglo.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2etwdeauv.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olhzbfpu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gt2xzrycovi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxptpckr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2iearkozb.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rcfekzif.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfeafpir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2qxdbqzpc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2ohvudptv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xuckesvr.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2smottvaz.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2kjqrlygw.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2anxuklpd.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2copqnmfg.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2lwyrcyzp.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gt2fistvyzu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2nmtqbnbg.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gt2cycevqkw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2qdvkhknb.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2ilxnijzb.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2jtgvqrfa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2effcqubi.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqjxitms.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2abfilywz.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2cawporgs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2pqwbsbgy.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zdvjzoky.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2lzivkkud.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiqsbxfh.html


<!-- 参考信息 -->