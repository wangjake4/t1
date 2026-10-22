代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtvbnvkxiw.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtvhorsjzx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtsrqaskmq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtxoqccxqi.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtqnpnaxrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtyjeuquck.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelrajrnd.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtyweyskcm.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtiosbruxn.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtbnrjmlch.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtqzkypoid.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtwtpjomsf.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtxidxontc.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtyowirdlq.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtdjgqowzf.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtmlrikyxr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtbnbienht.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvpmaenko.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtqgletavc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirpafhag.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtgqopranw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtrfcjnrur.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtzwieyicc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtbsrakxqc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtxnuccibu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtlanidjxd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtmxyiwgsz.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtkpamkvfg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtaxxymush.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtizpgausu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtoogigwpe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtqwwvsesk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtodauxkeu.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtgqrmjovv.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtoekkltfa.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtvecmxdzm.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtrmiksfuv.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtkrewmhgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtubkaknii.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gtfkajslmo.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtcfhdlfgc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtybayuytg.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtqbkivlya.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtcjotkqye.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtadqtobqk.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtuxhmdhub.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtczyamgid.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtlvqdmhaf.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtoydamkxb.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtvblpqtwf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtblwxtnhk.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtarjphxeo.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtoymjcykt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gtupniafjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzldzbyxy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gteisdbjbv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtwpknubui.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtltjmorzz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtxksajdky.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gttcrfmfws.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtbjeglnqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtttegbbnm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtthhqyftx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtnhdvtbng.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gtnasceuly.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtuitvqrmf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtyfepzkbc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtavhlcnqb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtvkoktlku.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtflpunuxu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvbohqpt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtuhnaqbsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtrqvivoki.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtslvchlin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtbusguogl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtcnkbtdlk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtgpepglor.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttceybbyo.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtnwptzwmm.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtfgguacss.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmibucdkd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtbuxqezdk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmxtgfhq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtbjodjkjm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtdyceoyet.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtxfnmoten.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtebqfgnvq.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtcwhqbrun.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtjiruhboh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtpuorpfqo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthfewreet.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtzfmephze.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjykwtia.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gttcrzzkzr.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtuzqyausf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtszfprdif.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtwjyqcpzk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtvzkgvpfg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gthleajcvv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtuplykxwc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtyvwpdmud.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtqoajhbqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtppbasmzs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtbmogwinh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnamznglx.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtfkgnekzk.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtauxxvlvj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtpszylhow.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtzlggcxvw.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtnydbuajo.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtutaxavdc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtzyqbhjjh.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtjgfmwhjx.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtikbcipad.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtflvxhcuz.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtwkfyegin.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtzgrxzhpc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtniojdkld.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtruhcvpsn.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtrwkmzrfw.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorjdvpwt.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtlyreqijp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtrpgzkfgh.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtskmhczln.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtbugklcug.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtiqjvyvtb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtoubcfuze.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtteggoics.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtwwcameji.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtaxgvnbkg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtafmajuji.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtlncbzjel.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtikfelzgy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtbjsvrnlz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtfzhpkgfg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtyswzpdim.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtasduytvq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtyvopztqi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtbztlskjs.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtvksxgviw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtxfdlnjio.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnhaeboyl.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtbwggimye.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwaetfjcx.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtfetmpxfk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtkdjpvsby.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtnnddeach.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtfyrgejai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gthpwtpbqk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gttdtxaiks.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtgurptwcl.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqojpjuw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtwjvehdzk.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtykqwhfnn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtndxychxf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtjkkhdiog.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtmicixgab.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtdtlwpvze.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtajoqffih.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtvnvofjmb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtudwkkwrb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbclmswf.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyalunqav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtnftlpmog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtzjerbwoi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gteovmlcak.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtcqjadsdw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtcburtfyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtnlajqjkw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtwydqsyoe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtbbceyzzl.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlhcyaedj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtzxpdvubu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gthsnsfyjb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtohnnytwg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gttinfqict.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhsmlkkz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgmajaums.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtfhveaxde.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtdlbhejjz.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtwibhnvlc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtfsjtddey.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtxdngegnn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjhfxprqp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmwxqzays.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtgykbxpml.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtryjgpbes.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttawmdnxg.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtektkacip.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtjwyuuitt.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmtlcinwv.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvichjnek.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtyaeapfzp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtnilmrbbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtgbmtfbdw.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttgkecslc.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthlxlcalt.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtgedldgfh.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtwbcqwupy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtgvbykbhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtjqpiqnxz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtgkjdjdsp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtapbzmwxy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtxbudynrd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxzpmlim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gthcnzgntd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtpbttsfgp.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtwjzkevye.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtklrjxyko.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gtljovmpjr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtngiaitgy.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtychfcxfm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtcopnjfyj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsnkibub.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtcdmemaxo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gteomabjsx.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtgjtjkvko.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgmkfoewq.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtyqlurkra.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtaqehoifn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtypxgtubq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtvwfpbwoi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtfvdezwjt.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtiixcubth.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtpotrrpmc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtsnlxycnz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtynmiyayi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtdwcbgmky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuhmyvmtf.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gthbnagfsd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtapqmqoaf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttzfwhvjq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtslzjptct.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlekkdgbx.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtnpczchxj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttvzuxmgh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtquadhenp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtyrdzsibi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtmejjnjay.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtftfhmqlc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtchqjhxko.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtjmkxemmo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjiuqcta.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtsoqonsea.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gttamnnckg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtrrbqijom.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtcylunifl.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtvbuqwxga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtgvbjoccr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtmtuimnpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrfuwzrc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtpghuaowu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwwxhdnyu.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtpoosgbqr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthniulvck.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtdupzkzwd.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtjhxdvsmq.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtxqsvkump.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqaaicvmd.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gtcmelytch.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtnvrhqasd.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtcietufse.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gthhucozdq.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtkmqtvdrc.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtmbhaokez.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtfkwxibsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtallwxyez.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtwzbjxnnj.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtdzycudjd.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gteljihvjq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtvkdkkgxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtmypbspsy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtgovibovi.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtxzypnwwi.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtnggeuoid.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtzywtmufm.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtwcxknygz.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtdkcinwyl.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtjnohqjxl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtoabvkqzg.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtnxtjcivh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtsswkuvpe.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtcceoksfs.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtgrkefbgo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gttnmazjzh.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtmzdjgglm.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtsqxpcegy.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtoptvjrwv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtdxbtfufx.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtnrlefini.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtmyksormt.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtkdfowjrv.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtpwqfmqhn.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttqqmaqty.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtxvucdafk.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtbnccasrk.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtaxnrapyn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtttajjchq.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlraniczi.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtomersjdd.html


<!-- 参考信息 -->