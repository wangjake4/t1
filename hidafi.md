代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvskoemv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gteiwfejqi.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtcogomajh.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtekukozzb.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtkdbgvryo.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gttjjqqyuf.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtydranfqp.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtccxpmhrj.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtetnombcv.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtkhxfxiry.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtzyirwozz.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcsehwor.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtfoeeokzp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtidoentro.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtapuqokoc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtaxwzawut.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtuktaugcg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtzduqbxei.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtlhhbmwoh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtoyvakuvy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gturtmobcq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtujylefay.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gtajvipjhe.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gttlpqwkli.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtflmoiwyb.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtrjkeqgos.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtolhjwvyy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtisneeuyv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gteavmmivq.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gthawoxdgs.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtyleutwlf.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtqakfyrlr.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtxdkmwfcl.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtyvjnzhac.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtlkrgtrhy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtecuwnsak.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnullbju.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtilplroxt.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtdfujhnks.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtegptyrst.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtwupajupg.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtflflhlsu.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtvzwcqnpx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtqombdkez.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtmjkuuycs.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtordziuoe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtfrfxaqyo.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtxlzrastf.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtizywmhom.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gtgkbvmcdm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtpvcyzqcb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtoevfwivg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtgxwfowte.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtdjwqabff.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtqmxouhwg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gttedrcves.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtuemghvuj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtdujyacbj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtbvqmcags.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuerpkdd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtaigduqxr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiejwozki.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtffgjdfwz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtqvxteqjj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gthnfhxrcv.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegjudmvw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtrndfcrag.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gthupurvyb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtpayzopaw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtvafnbpmn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtstkzxiez.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtufyeryuw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtdfqshodf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbtmspzy.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtljkgrksy.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtcbtinqwi.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtejbxyfuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtsjtlmfbr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gttfdhfgir.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtspqjsjqx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtvlypcsza.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtghdevueu.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtruqsllvc.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtksytjdje.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtgzjidkeo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtpegbsskp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtpoyqcswi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtnhqukgcq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtqmpqdnqq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtmqfyycpb.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtrcksbsoe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtwzzayuxd.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtgrnktwsm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtjypaejqx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtupfidrzs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtgmtlesoi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtsydgebke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtwggiksas.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gttyfydcxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtiuwazdsb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtwvpxuxup.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtakhzaqqk.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtqvqwuoap.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtwejdxnzr.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtcgllfuet.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtdpjuxffy.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmcoavref.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtjdmwxsks.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtpzebhfmc.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtekcaqbqi.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtozrrgofv.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtpxeromho.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtwaxsbdbq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtsvwxdkvs.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtcgfmpywi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtbltkbems.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbowxvjef.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtzdrjmgoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtwnzjcvim.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtvxbkdzci.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtszgnzqan.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gthkiwprdt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtpxewhwym.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtkwhmyrfg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtrhirzfdo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtbwpitvco.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtfgqjuilc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnnlgjgq.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtfiqeddjg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtyzjuakcw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gttvmlgdfm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtsodshnlf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsauqfuk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtfqvoyvxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtqnjjkatb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtdoukuawl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtgyydibqz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjgahvxje.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtwpzsvugd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnrsynory.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtmvebbhtj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtnqrvekss.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtkefapwbc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtkipruqsg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuhbyqbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtfkznyije.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtvztuqkyi.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmnnzmrya.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtxkovdgyo.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtvwzmjmdk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gthixmnmqt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtuhkatmay.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtpapspxiw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtmxabexuc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtclycivhf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtsafdpwrd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtvrirgwsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtahvswomd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtylqpldel.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtcohpwyjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtcengwhwc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtqfwkbubd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtcfzpxfou.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtqkwzlsyt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtznytktkf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtzzzpsvwr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtpcxqdtjf.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtmiyyfias.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gteeuerhnh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnugypapn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtezqwjrdr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtdnrgghnt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtxehhftwl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtjdtsejba.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtohqyffmv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtawpphwnc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtqftstumh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtotntrlye.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvhkmrwif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdoibgmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjolgcsiq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtyowvbpkh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtdqeuddef.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmjntstrz.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtzoqylapz.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtfauyoznu.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqawbebhq.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtistgokue.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpbbwjjgu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthretwgji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtoefofbmz.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaahowexg.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwgtyukqs.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtakjhnwyy.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtnlevrpvu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtkpfvwrgz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtsycsnwmx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtgqtfoffv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtcczwydcr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtinfjmcxe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtzcphhzfx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtsamapdxj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtkmkyxold.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtyzgcneks.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtleimtqnz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtgbpnvpuy.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtolpyngll.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtrdrmewzh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtsbwjxutl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowikbhyi.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtmvyaqlwh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtwtleqepv.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtwrqgvvfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdrnfnhgc.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtvdoyhuge.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtruwxspgv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtzulrbwcc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtgkenhvuo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtqoorsjrw.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtofxkpffp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtjelmuwbl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtdfknieka.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfempxmmk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtrshwqauy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttojcfjmp.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzcyyeqzj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtaiszqkos.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnrtnsflb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtxutpnevt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxktdunw.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gttwpkilmu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtydjmwitt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gteodigwtg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtjtdziwfn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtvnwuiqmh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtczubfnir.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtedlqvtbh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbzvtgtdf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtwmrxhrtx.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtcbfxgijm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtaqxwcvhb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtbdkpruub.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gthqickuvt.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtlhdwavhn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtsatsgpky.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtbcpeqqfp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtzizzotiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtehfcggvf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnhasfohg.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunolzehb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgaaqkdgp.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtiyfqkfsr.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtymqjphtc.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtwqfjpeit.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtigroblmw.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtskbpqvws.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylsaephh.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtmtrwckpu.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtuvheyywl.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtioagqkka.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtvcpydhfc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtqckfqsrn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtjahkagwe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtdptfikei.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtyfawjtey.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtmejckrlm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtjwskekax.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtvefckmad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnnxzvfqw.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtuupmjked.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtoiozwwxb.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gttylhbzys.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtqeblisvj.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gthrgrwehl.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtwnzxayid.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtiitnqceq.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtbchjouwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtwbkzwliq.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gthuilbbgz.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtgpwsldpt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpcucfjlo.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzofosbyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtdaddjcvk.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtfhjaoljh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtnythqvzs.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotlhytkr.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtxkxfnkgr.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtkuajdwww.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtvmhodqmi.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtezvpfpcs.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuljsisap.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjagjjaci.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzoahvgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gttgvynyil.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtubkvgzdk.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtmohdvgyr.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtehdchpsy.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtlvrquckm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gttmwbtihw.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtayzyscds.html


<!-- 参考信息 -->