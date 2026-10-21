代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtyhinwxgb.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtprdkwdon.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtadoqgvau.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtxjqfqwld.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbxqfeeq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gttnpeecod.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtqzttzdma.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtiybnmbty.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtvgfmepbc.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtqpgzwnbc.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtkidljeps.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtlczjdnnr.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtudlaobfl.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtnrdcaavo.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtzeszvuni.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtfkfgxszx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtrxyrbjdp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtsaxwolzs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtnvwmocvn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gttrubwraf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtsuvizotv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtqwfeouwo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtutwmxste.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtwhhojhye.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtoowvwehf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtofbzozoc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtnszefhql.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtwbwjrlcn.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtgarajzey.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtdgbpbiwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetgimeed.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtcsnxfsua.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtuzntofam.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtawxpbgxm.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtkoxjgzse.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtujnqxbqs.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtxjydzvhg.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtsiglhvgq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtxcwnvflt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtjmrbwffe.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtpbjqyzwm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtzqssxfzp.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtimlsnpjw.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtdktcimap.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtjsljfpac.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtpxlehisd.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gthdqcczxr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtftyxaeys.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtxvdlqiiy.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtvfyrlbsy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtimvankkt.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtpdynxxbs.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtqheuynug.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtnyospluc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtaxjamvyf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtuzfmztmt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtyelhaszi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtfygggcrv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtjjclonai.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtwyhciozc.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtbwwxyljn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtbyqzfabb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtxfozsiog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtzevcpido.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtlemlnofs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtutyvpbmr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtbejxwxio.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtcdbbduht.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gthlghxgvg.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtzfqzqeod.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtshgyaewj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtjaqwnogd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtmkgcdvqo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtdmjcxgha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtpjlcdcei.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpbwhubjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtuzspkhoy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtiqtxbfjd.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtpwgefhsr.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gtkatqigpm.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtidqfqixk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtzovmnhfx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtgprsplti.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtxhwzruzu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtsngmlmyx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtfreykhow.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtxfupfdgn.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtmyintnjc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtxnfbkwad.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtjsdadjui.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtzhgfxqie.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtvnibyqtt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gthypjtjua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkpydtfh.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtdgaumdan.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtuageobhb.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtczfcozor.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gtuiryqjpd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtwgdzttmf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtovgnztoj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtywbehigb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtwzgleiss.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtqfgoursv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtqyposdse.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtwapmelgw.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtkxhnjmvw.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtsjhkhtha.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtkbuuijwx.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtkbqsesiv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqhhwjqz.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdigchbat.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtchshmqsr.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtbxtsrjlp.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtxcvulvzw.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gttulcthvu.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtnkryzbpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtbmmjhtxl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gttysifqca.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtfodvvmft.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtgrsuspoc.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtenepzawz.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gtifvnfxji.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeqflztp.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtpngsxsfz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtqhlfalit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtidrannwz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtudzhykue.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtdwubsoqv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtgrxdafuj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtvhflqzkd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtbejogbqf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtlutszfwe.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtmlnvnald.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdfctturu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrivguuuw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtmqaxfvds.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtnykclszg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtcxzqkvuj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtzyecikqs.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtwlyzkrga.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtmamphhcl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrhfcnwbp.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpatsuquf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttxrfkddm.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtucvuzkvi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtcngdcdhg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gteglwtcri.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtvumtacxf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtcrwjrbky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxrsfxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtfnqvlyry.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxvscjflq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtdjfaffzn.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtdrvjercv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtmxnncjvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeahdxng.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtjpybdqho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtwgxmpwsv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gteghddysz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtrmxkfhvz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtecqanywq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtfvibuxdv.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtmwmgfctu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtdxggdkab.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtwufvqwer.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtpuuvepsl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gttirupjlv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtqugshyhl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtcczzdffc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtnstwcxth.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtzsspfptg.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtcjeglxgq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtyxcrbwzv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtrmmozriu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtwlnlumff.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtqsvlnuxu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtahcbkdft.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtsfvcthen.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtykqobmha.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtedmnhjaj.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gttxaxrcob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtpobhqixp.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtwzlbqqav.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjamppsae.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfkdypfsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtgonzwjjy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtidunxvjk.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgzpusfvc.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfzcaogeo.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtroapgqrt.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpyziwad.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtkcxxpazo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkprrcyrv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpizsrsha.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtvrsukpcl.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlkrmnfdy.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxcnzvqht.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowzefffi.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtjscudjht.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtpzsaqovy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtabfiovcj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gttthkmlli.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtkhkllyim.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtvrvwmpet.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtcwafymmh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtypwtlrgc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtkmgjolas.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtrriieopm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtwhttxrkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtfksdztga.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtjtuwvqbq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtamdvqrzz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtrpyqscyn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtwbjgqeeu.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtuzhccpar.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtlcleouxj.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtwjghpajl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqldlklcg.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtoxeltrgp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtltmprbxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtbcygcory.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtisoaritk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gthayqqspy.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupjhipup.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtoijrnqjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtvnekhlcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtssrfrqyo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtllqefpyz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlxmhyznn.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gttgmiywjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtpocnrpfr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtulfimiil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcszyeseh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvotugmpo.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtphwvzbof.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtzzbppl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgkbgxih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszvgyrkb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdrmcagcf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtpmjqowpk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtlxgxcege.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtbtwdvoen.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtuvvludha.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtdmjardyv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtguaioonz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtcylrzjcv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtveeotxfj.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gttkbqlrsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtzimysnrt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtcnrjutrt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtumomfxkw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtsanlniti.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqlcbledh.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtwgadpjev.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxjhoprta.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtjoeeglfy.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtptvvshov.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtzskkpesu.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtjhlvuzls.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtaiwyjcaa.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gthrgewqzq.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtqcjdytga.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gthmunubtv.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtbpmrcrmt.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmkxiauh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtdzikmvtg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtrstwhnlg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtjexhxxlm.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtxcafdyec.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtoeshdpgg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtuojhtqwv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtfrnskvvz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaeymbqge.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gteistsvot.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffnjxkws.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtxqkfvkfl.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllexbtkh.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtrzjcjqkq.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtwuuwzgcs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtzaiplhob.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtdweeuuxq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtitbrksop.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtvuamcfxc.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtmylbegcg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtklvegavy.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtkjnpvaob.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtridrdbir.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtybgjopvh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtjksqpics.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtduemlxwy.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtqtmaalcc.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtxdruwsic.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtolgjqldj.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxiyqdki.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtprpameji.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthndlwcqa.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtrysbnoem.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gthnpqsumk.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtixrndfbs.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtgggmldmr.html


<!-- 参考信息 -->