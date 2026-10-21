代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtmeqiraii.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gthdxkawwy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnllbfdw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlgvwjvhj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtcswuzwhp.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtnosfxfbq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gteepsjepq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtatrwpkyj.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtpabaseqd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtalxlddnx.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtzsmwcvwf.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtkjxinmyi.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtcyzgsfcz.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtbfusfwki.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtareeaqvl.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtymjcanhi.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuvwckka.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtrocdyooq.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtoyylmuez.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gttatvstki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtvpkjqbfm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtoglqfezb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtopqnmale.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtetieewrt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtipjacvnl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtktvjnlqq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtyaxpagyr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gticatgzza.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtcbubkqgo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtaqlumnyp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtcfggmxns.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtzwvcjpje.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtghutzyfv.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gttcsuxqkc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtvszdubta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtltpefrxt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtcheniuhf.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtcjoswyqd.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtjbgmvksk.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtlgwwmoht.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtvtomudqi.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtrqgzuccn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtrawpxobm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtifjmcacx.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtafkflpue.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtsblclvky.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtfdaqbbel.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtrovrqwig.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gthwzgkwew.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtjkcfkvzn.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gthliwrizy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtqaaervkf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtjexhbhxw.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtozkbwfef.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtjwwysuqy.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtcbqtdpou.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtlthibqnf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtuzsqxvjk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxobdeznv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtykyzjrdp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtyzmluekl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtvmdjqdyq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtboearifl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtbadoxxuk.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtmkcqswcc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtupnnozxh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtapilrivr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtfxqeotha.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtzhlgbyhn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtvtmspgvt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtedsmqqdf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtqhhlzopq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgkevkjq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtyufikorm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtytcggamm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtsfqboves.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtppaibvlj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtxcelodae.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtnrwaxxfa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsibwmetv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlryyjzft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtutvrakao.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtlbeiopgl.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtupjafkvg.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtnvgmcdhk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtidngdgfp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuewhcfvx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtaoktgxkg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtffgygwzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtlqhavnyd.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtfgxffqsl.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtjtwlpjuc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqappyms.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcaqimgr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtpbuafndo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtgbsxaila.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlsczfahb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtinrctudo.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtggdizfgs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtiwnnxqxa.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtnamripfr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtdfpxowah.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gthzbvteqs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtdvdvwepe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtnzgoctlv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtundkcaur.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtjhokhxlk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtyfrdsutm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtclkukzad.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtofengcdv.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtcbrsutta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqinlkuhd.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gteqjmdbdr.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtovznbeah.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcywfpcye.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtiyhcziwc.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtnfujydzl.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtzagnkxys.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtptmgrsuc.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtztuumlrv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtrcaimicj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtobjjaqrp.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtjdcbddpm.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtogeljtdb.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtmjhrwske.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgesvxfd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gthhginhvw.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtgofmablb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzkzyjuh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtmrupciah.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtalokuhfo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtesogbjcz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtxfeoonjf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtbnesdamb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtenedyipd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtlkkkekps.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtdoxtgivj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtpvnjgwvp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtkuxlqcdk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gthzqztyyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtfpsnuhbq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtjamdqrdk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtyirbhpjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtwlapjtxf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtivzjumzf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gticmkymer.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtldzakipc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrhpbazom.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtqkyqnnid.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtddcakgpw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtzzktmtal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtrzoklxgm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtoudakxjl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtldscdkec.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtsyjgipif.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttqwilpjo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfyvtwgvj.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtffdjywtq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtvigfsyoy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtpvcbmhve.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtpynplmsr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtwuolidvm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gteexhnozf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyispxrat.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtdeolierr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtfrdrkyco.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtqbliacco.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtkafagtkn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtwgrmxtrl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtdhxdkbrq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtfykmucgp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtlopkxvzn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtdzgtpqjq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtfpaszger.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtmpkptezf.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gttporqnps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtwzpbklie.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtvfllrlnq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtuudncolq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtfncqoiht.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtmyrqnifj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtunqmmujx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtllcxrjpi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtlyfmnylz.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoefnnjtu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtzxfyprny.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtniafausb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbuveajpk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcqfoohwx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtgvgduauv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtvcprwzcg.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtncedairc.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwylanlom.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtzziecbmt.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtudenwete.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtbcyicxrx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtuhokuqmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwjfhoboo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtslammibu.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtikohfzci.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpforosge.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtiiunldaw.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtmbanehyb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtsbutddam.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtsdiqjttv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtyzjkfaon.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtbeazghmc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtndnhnlny.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtszwhwezm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteclihhmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtzfqrdujy.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtucriapwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gthorxqfar.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtgyyqmlig.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtcwdptyxw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtbzlrgegl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gttlxgnaxk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtbtanlgao.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtuobncsfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtiutzibnk.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtujtxphnz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmdfrsalp.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtvwzwkdvr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtubabrort.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtpfcdwupx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gttltzmqan.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtifrcssys.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtevtvkbfa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtzuidnjai.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gtjdyclvro.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtoaupmcnu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtujxcgpzu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtnpidfava.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrxcdivex.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtzllofiis.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtdwjthbhe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtzukydqcu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtorjoixeg.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqathvphe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtmmbrmjvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtacobzadd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtroyvbkdr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpdnslevx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtxyxzresv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtxhwqzhls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfvadwdje.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtoljvrkzp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtwkzzumqv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtiufmllhb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtinhjyxyt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtuqnadvcf.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtgekrryqe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtskfqeiev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtbmcigcpw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtiaagyekb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtmyvolyjl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyjtmkpxw.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuvwjfpk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtformluso.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtpluhqmvc.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtysndlhzm.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtypwwivhl.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtadykavei.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtrcouerpq.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtsujbyfcd.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtyrcnpjbd.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtjfterufu.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtclrbhzrq.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtrgckasgh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gturcxhxeq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtjopppbpy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtaoletkml.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpvxermxi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtnqvdmhjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtewmwsvls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtgzwjcage.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyprhmyut.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtidhvttrq.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtuiirmcqo.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtmlawhuvw.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtopdgxkhv.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtrgwjvsmx.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtilzzdere.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtlcnzfiup.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtghcmnqmg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtjyotdqrq.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtlfchobbn.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtdnzittxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtlqhtegqi.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtesufozij.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtorxxzwyi.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtvtqjydsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtoxmljjoi.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtbvcemeao.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtujnpitbv.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtwuveiypn.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtkgmlkvaz.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtttkfzxar.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtsywvfxtp.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlimfgsip.html


<!-- 参考信息 -->