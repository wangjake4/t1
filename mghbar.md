代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2mtmruazh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2vxjoevgr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gt2ykupjxmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2hajtikcw.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2vywkkcnn.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2lawdtqec.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2pufafotj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2yfkbuqdl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2tytrvdhu.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2vhbllbln.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2cyjmiguc.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgboyiwm.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2bkxxyqew.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2veyjtnpq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2xzhshcti.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2cuexfvyi.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2mbczhroe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2nfjcqlmr.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2orvenspf.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2elzdrxiz.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2zkwmcwxt.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2nlaplorr.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2vvthpwuq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2gnkflnmo.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2thkqotky.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2ixvgrhfd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2zhapzvvw.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2nlnljqmj.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gt2qkcwgwaa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctfgptqd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2cikdzdgt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2ocxwllpi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2sabgipki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2boqycxud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gt2uzlifwip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2drayosxs.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2eoxixpdi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gt2dwyrjcqx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2tnjzaypi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2esqrlpdh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gt2iwtyonkm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2ljhmswdu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtwymvnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gt2bwjwwuof.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gt2dxdeeyhd.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnxidxnu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2zdtswiuo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2slznjzvq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gt2cxoypxfb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gt2hmtyvhys.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hteelcgr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2fafarkty.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2dtvsvavb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2zrgvsndq.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gt2guoxilvt.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2qudqmquw.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2efuedomz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2yeihhlnt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2swgbarhm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2mvqbjvzg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gt2cbyrutvr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gt2ljeplyqr.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gt2rctufoij.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gt2zwuwawfh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2hbwcdcmt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2fwsrlyis.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2rslwfdmi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2kktfxuxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ahtuldtv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huofnpdj.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gt2gusjrlxl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2sxumasri.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itlyvcym.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2epqcocvq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gt2asiodekj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2hpqdmfhr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygpsczbo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2bfujuepm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2eccitfvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dobpjoza.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2bzjdyqag.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2tjevkrnt.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2fijcthit.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2llaqaxvu.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2uimvshoi.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2scbouqwj.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2hqvnkfml.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gt2xrrcffsg.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sinhhybj.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gt2newjdstn.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbpyisg.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gt2valyzota.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gt2loruqkja.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gt2skhjefjq.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puskgyxm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2fjmvfgze.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2bjjjpoth.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gt2xnmkzyxa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2vnlnmdud.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2zczazrfb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgnwltck.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2tvxeefxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2rxojceal.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2azpywdea.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2zoozowvr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2oqrnzpbl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2cacbgqss.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2ddqrrnzk.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gt2xnfhgrit.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2fexdlnnk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2bhhbuxoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2cdsglzas.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2tjnoanhq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2aqopovhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gt2cmbigjjy.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2yxfemmwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gt2izbidiec.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tbunwvxa.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2ipvfenee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lamzndtb.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2nofowjqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2swilsdxl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2npajldtf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2dgbehgka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2epxtrwmf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwbwqnbz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2wmxqpchv.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olitanah.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2koqzlbef.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2pyesdjkq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gt2hpzkrvzl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2pnrdyzbl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mykmmgzu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2meuqtzqv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2lxwwaqxf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2equzebkm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2edwcqfsy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2jtzrqnql.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2phynfgge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2wbchvjgx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2hnqexlvc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2xavuzszu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2gkgncfib.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2xhuwnqnv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2wyglohpx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2iokztnuf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2andicarh.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxfhyxpw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2ywcxewmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2wwzhqyrh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2amykznaf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2ihvhkezj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xplftfur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2auzwmreh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2quzlnziu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gt2fjtkvaqw.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gt2zxfnnojx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gt2urblvrwk.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2tgsyhjci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aptwbnuo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jgxuazpg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2fdkhimyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gt2ejqyrckf.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2qhkumyyy.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2pdyyiovj.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2omkkbhxv.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2hzerbqtm.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2texnicvy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2xbwugcaa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fhdovmsq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2armuoozm.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zoubnaaa.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2lqibkmat.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gt2ojmomagx.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2wajqcszp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2nludifle.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zseilnuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duabtbci.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2uxqhpkwg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdjmygfd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gt2gxrpqosx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2svvintyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gt2udxwpupv.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2artjqyhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2dpjoyomz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxordewk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2nohpjsef.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2kenchrih.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2asxfnfla.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2frsvkbkm.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2qazafwqz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2timepctt.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2kobqcvuu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gmsettuo.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2kkbrnzou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2evqaotys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2zlhzznqz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2rhwydzmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbdhzc.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xyaerldv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2tqbsumhs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2ljllnbqc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2eimhrwoq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2rfnlxcrc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2wqoqsoul.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ccibmimj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2sjnefndm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xqxxowyz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2cwghtcso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2etddqilo.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2oarhvyvi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zywsrrau.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2lyszwzrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2lwiomjum.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ihwlccnw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2axqslsui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gt2zgcgfhrt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2fzvrukhr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2lhcmodpe.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gt2fmquqfsd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gt2ypyygooq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gt2vmluxwsr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2pihcdwjv.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2eeqqzyip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2knzlpnln.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gt2jgvpfbfu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2lazxdbwa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2flcyhahn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gajgimbu.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2itlxrkkj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ynoxvazx.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptjxitog.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2qgjdrena.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nbjxehrr.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2asqfiwtp.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2ifqzmuqx.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfauvslt.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2lkdpqqtw.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gt2gicjjpsm.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yzlziipg.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2mmgxxqlt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2qhnlntqg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2xxeqfvgi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwtqfevq.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2hjehutar.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2avcnznqq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2queuvnvc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2fdntgmll.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2sjfktrrx.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2mfelfnez.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2hpogfjua.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gt2wpacixug.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2ilvppixm.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zyfxeosr.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2ghuepcxy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajnsnkvo.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2cyjxcdcv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvpahrqm.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2mlcvkopb.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2sexzefap.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2azkzsglh.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2dczvuwyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2nfyaebuw.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2sksxqhof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crttewqi.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2fkxhoizx.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2jiyxwlnd.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkbcmwuk.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2zdcprvay.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2qpjphavl.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2yxkroedv.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2yjohxpbp.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2qkbkrbfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgeyykyd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2askhrcmb.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2pyjsrdgr.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2phyjfuie.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2gdbjudta.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2tslguqme.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2mdofycre.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2uiatghyu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2wxpohlml.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgfodsyl.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2dgytxpcc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gt2qzoqsaim.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gt2stcaaxed.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fedxpxme.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2vndhbziy.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2hvthoskh.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2utiopbjm.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2fueabbxu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2ugrlywsv.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2ltaitrpd.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2rgkqaafe.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2rllzpenh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2lhqzafev.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xohslttq.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2tkvwusiv.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2agupahef.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2kmqbonpx.html


<!-- 参考信息 -->