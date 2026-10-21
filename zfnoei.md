代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtwzvfrgpl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtoxxkzpsy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtjqgcvwej.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtsqzddsbv.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtfonpwcwk.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyieoxfs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtfotouvjs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtqawgauor.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtexdusxgv.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtafvjeosb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtcikboqpj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvnvrszwv.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gttdylbkrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtbdbnupax.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gtuidzgeoj.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gtczqdvuof.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtfvsinzah.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtgvowmsrf.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtifltevgw.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gthzavyicm.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtakigdsqa.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtgiflmfie.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtebgzytsn.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtbirbvpdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzhtqhyhp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtxkxtgxuv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtottwdlbe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtmfbzkzdf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtybglzdqq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtiywgnhox.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtzkcvuktu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtqcnaugbw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtehgntsoo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtdfqiodnp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtomrkmujq.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtmfpsryro.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtggbpunxh.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtngoeando.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtskckzmyy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtixvmuxun.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gtghtbzwem.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtmtrwagjx.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtgptuaolw.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtmyjidawy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrdixivo.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtchvfznmy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtqpymsvap.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtudkbjxsa.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtfrebsorl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjurznifd.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtnvhgphqb.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtfjuchkmj.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtgspbvqva.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtrjlnrlcv.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtyjyxqylq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtnjnyfihd.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtokyjptwl.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gteesrtmut.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtzupmonyc.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtwsbglaof.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtcgqtijed.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtsjkdtcak.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gthzmxxsme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtskcjsfnw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtuscgymcx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtqubxnnut.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtkqvcwkxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtdnbowxvh.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtlrdxqvyu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gteuiojoaw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gttmoksfug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtwllswxge.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtewgwacjz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtbsxqaxvk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtwkuezwjm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtsddwyjiv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtmefytc.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gttynhehdm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtsmeerxbw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gthzhehtib.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtjqphyvlz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtinpwpfhx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gthqkpsmng.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gtfxomkoan.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtxppdnuyl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtltakahfl.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtlthbfuxv.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtrtvcejin.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtgrhjysdx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtgawbwf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtjwtogyhs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtbclbpooy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtgtodajjb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtoqzzddyd.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtzdukqacl.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtnnmsjacu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtkuhbhwwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtjqacgrvd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtgkpihyce.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtpyzhdlho.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtjchbfixo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtwtxqytze.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtbsntzmbk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtbdlwdwiw.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtuhjzrqjm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtbuopazzz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtiznkacvk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtcbbpznsu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gttsjzmnch.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gttvcmfnoh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtepdsqemb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxgmawhj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gteajmznpl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtkpjjpnif.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtotqabyhi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcyhjhxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gthdoxcpzr.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtuqwflzzw.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtxpigxzng.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtrhsdwing.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpdktgem.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtamugbret.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtevzbhggp.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrxvvxvi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtmhzflrji.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtgtknbvzz.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtwqiedvhy.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtwdjequgs.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtrqeqvfyp.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtsustgdmp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtedqqkxtm.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtgsciudng.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtvicumeuc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtdqlasibs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gthqpyugwv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtcgvqdisy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtxihtjrom.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtfpgxssvi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtsujderxx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtzpevkubn.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjdhjcsr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfnkzwghb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtfryjohnp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtwtaauyyv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gthigcntlr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtyxkxvaha.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gthryzarjc.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gttqieelte.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gtkexfuexl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyyrarark.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtipcjxazg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqxacizfq.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtsnrwlogb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gturpvipnq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtqgxysivi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtrkkmidnz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzludxwr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtrrbmlsqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtcsltsabi.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtnebozywa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjslrrwfn.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtyhbuslmn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtnyvoqrgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtoslcbsvs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtgaxnwhas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtztmortpy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtmltppqzp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtlpwdiuik.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtfrrlikwf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtvzpytmdp.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gttgjjztjv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtxnvhxfyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtnmowmeqi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfebmumx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gthfrclpsv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteksubbwl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtzbowgwcu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeluwjhv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtitjxkknf.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtubcyhllr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtsnpjltsz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtodepbngh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtdxhbvvjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtgextroxg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtzlkihxqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtcrhnizla.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtegqxacfv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gttytotrwd.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtexrhzbph.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtkmzdyhkz.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtcwkpywja.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtapyecwyr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvrilzcgo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtkgunynbr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjuypyqc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtgoqpkupi.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtntyeriva.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtaxfbogfx.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtkvuhncla.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtfsuhhqje.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcadgsyvp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitqfsxre.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtjzslvqan.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtlbuuoiqv.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwudjeyuy.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtxuqankiz.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtdgtxgvcl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtatysedzs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtfebyhafg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtlhorltwv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtowsxkxuy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqdctiwf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtzwlvqghe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtwnjtrpoc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtaoqgwykj.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtvepklrbn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtgogbynww.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtdwtifbck.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivswjyjn.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtpdrjcxzz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtnrhiuqup.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtoavzhezy.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtihcgtsqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtssfxbqdb.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtnprqqgrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzbbjpyrk.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwkemplox.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtauoonynj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguarlplt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtmjnzakpl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtcrukmtab.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfmudnpdu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtfioofjzz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzfiwbyp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlbgmfzaa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnszrthnl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtvaemftxx.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtopxeamxi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtndizwzgm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvysnjcnw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuymqjnai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthmomofbv.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtpnxuelvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtuhcgzxqh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtfsysclpw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrefpjzdu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtcqgeybdr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtrrqqbwfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtpnrjrpum.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtnusskdhd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtxhfcxahs.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gtbomlycyx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtmfmipibv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtfqbiizqd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gthlwbmqcz.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtqbfbmkto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtthkqzsnj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtdmlpqnjb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtpedfiwal.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtuzrukvhy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtspwdktci.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtnempfrlz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtupfdapaf.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtpxetnwng.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtgtflzejs.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtvlnmmcmy.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gthkmhyapp.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtjonyvogd.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gteidweqxu.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtldpwwbfm.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtrgkdokyo.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtmbnagxcx.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtilfaonbw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtntcesesj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzljeatte.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtlrfyvuna.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtrwjxojor.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtgsdguzuy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxzyzwd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gteqjqwdsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtgkzkjfbl.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtqzipcelh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtelaltxnh.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtrzlkqcwr.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtpdeslyct.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtdqslxbca.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtczkugkdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtfxmsulsn.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtihjrdfko.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gteycqbcat.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtvsfeqvam.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtxdntkuqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzpcnepjw.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtnnbpsgct.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtrktipodm.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtpkyyojeh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtvvtnnync.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gthroofnfc.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtbnyqmrmv.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtdloetssn.html


<!-- 参考信息 -->