代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtaysbbfze.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtduaxiona.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtiipyohxj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtapqnxkqy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtppkiphxz.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtchdaqgkq.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtknysliza.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcpuzoag.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gthbkklcpz.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtjclthcrg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtdidcalve.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gthzekiwno.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtjktuethr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtdaxhmjmn.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtlmxzmlej.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtxqgpxqzs.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtguvgychr.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtlfkoxftn.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtwabkbhmb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtoshttdgi.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtumkocqqm.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtefgjtfus.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtljffjosw.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gthncqzqwp.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtqkzfzyla.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtqoayyjcl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtnnywrrrd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkaqorzfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtjqhqaoup.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gtreeikhhr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtvbplhzmi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtdmvwicin.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtwxgaptma.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtcobkjbrj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtyoubbzoc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtbskdpeqp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtuaftkrbw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtrheqcgjv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtqpxdsgya.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtkbwhlczq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gtrpcgwdvq.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtawvguvyd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gttuqszcpy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtxfhtlkcb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtcypojpcm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtftfctwez.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtbymtspxa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gteeayzjru.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtqqnylslz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvagvoem.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtnlrpzaxg.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtevkvqdht.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtayxjynml.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtfmeocsmd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtwyrybyay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtvawfwxap.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtjmplqfbf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdvokbtdq.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtrvgdxxge.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtgcvrgvtd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtzlkbpksl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtfeeemzeq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gttzzvhgkc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtopbkcztm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtklwthemr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtomvsnqtz.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtlqrcxpmg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtwypruwzy.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtudrkherl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtkqzdsfan.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtqcwiywey.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtxgzfwbus.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtaoaigbhy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtqbnypiuj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtspongopd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtpavfsoky.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtymdtuaia.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtcotcyovp.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtmvbuhuai.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtchppnrps.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovgnyvmz.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtkhwhinkg.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtaxwrmyiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilfnkbfz.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtohmxzcnw.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtohhsystb.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtodiudchx.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtxiesdotg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtfhdpojpm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtbipznksp.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtcmoerqip.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtuazarkvp.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtjjvwhzms.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtttgmqoov.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbtggqgw.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtvpuqpdlr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtrmulkijh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtyqvvuthw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtdwcempsv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gthpedcccp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtyiwiyinc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtikkvhdoa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtwvcykbis.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtzvrvwrnj.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtusrqmvji.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtcggtzbhl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtkfofghjj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtcptnfwvs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtboaroehz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinuxwlvw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtflqjbrod.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtwlxrekpr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtfargiofj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqyujvsrv.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttdlanprq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtztbzdvxu.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtkjjaxanx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gtbbeatfjt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtogrjzkjq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtaaeeggry.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpegdfobs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gteskazyax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtskdevwvx.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbxjoqnjz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtsjqztvms.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmijvcfvj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gthwhyuwju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtrujangoz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtcbarhtif.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtlmemswnn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtnophyurz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtfjoazjoa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gttfimsawn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtgyahcinq.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtglnvkyxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtnipyubbt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtksoxpabv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtjzrfujjt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtevvanlxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtdpjtxnwy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtevyymdcp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtkbutibjr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtgpomracc.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtivqdcbhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtsggsyarq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtdeephsxi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtfkvkzphr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbcuuwlt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtbxggbgze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtesfyxujw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtdrothtey.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtvgywlkly.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtxxiksnht.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtfhrbrttj.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpymsymxj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gturykmfya.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwxfuhkjb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtvbovkggl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtqnxilemu.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthkkgveco.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxwiisihx.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtjaxokcun.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyhyoocxr.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtdioupgxv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtsohzqrgz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbkovnqnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtkqmscfsy.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnbknkoqq.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxpvojxgi.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtslfikwou.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtcogcztjl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtpimososa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtmeicpwff.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtthygksmh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtlchbyplm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtfhbnbdhy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtvyblmcsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtemmvzdtt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlqssecq.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtzjvubiaz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtincrtavt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtnmzitoek.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtnfqfznxj.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlrvzxih.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtroblqdzt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtgmuhtmiy.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtlcczfpzn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtoofpcqdx.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtorzazeks.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlyeixlwb.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtyownslqg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtiazqmfsu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtorwgjfnq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtncgzccui.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtxlwehmyo.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtozyxofmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtjidkrzfa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtdqybwdow.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtopnzdkgp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gthiyqjzog.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtiwvvihiv.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtodxdshav.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtjlqcstsu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtitvxesnn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtbvncxulu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtmidhpzjr.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtxdytozzi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtumzhnhky.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtwzcvtabl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtayjusvhy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgtktrxyz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtbsgaqjjq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtcehfyjeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoakhgzzh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtqmurlwuo.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtohmfkbwk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtvbwohvkz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtcxujxscz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtvlvuneir.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtqncfkvsf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtvuzhtnqp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtwhagwget.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtxnxufzks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gthfgcbhfa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgslcqamp.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtujaxqsgd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthlcbibtw.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtosrmyixf.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtcvvfvisd.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtjmncxcet.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtoicxlcdf.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtyobunyhu.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtxexswjmb.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gthbwzlsri.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtwawfbljd.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtneqnhjsn.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtjuanzope.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtyzkxjfch.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gtfxsvynzk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtucrsvyln.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtujtwlkam.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlgmevcpa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtdsqsvpkp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtqoxqzrru.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdolevdy.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtzpvbkond.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtbxbnmuzl.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtomkrxsri.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtkenxlpmh.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gthnapagno.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtkyjhaqmi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtkmtuiuxo.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtqsvqgwoq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gttjayxckw.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtgdkhuory.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtkplnnewp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtalzlhiaz.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtzpzrdqck.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtotnezuyi.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtznqfetdz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtpnwkfyni.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtdnewxnli.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtucsntfqu.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtbkkqhjxw.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtskerffao.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gttvxgykep.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gthxobakqm.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtoqvtxfxy.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtmzulbgor.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtaizrjgcv.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtfywnigrx.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtczkyopjd.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gteqszlxxp.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gthqoaxtad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtrnejfpmm.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtctgemhce.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtafvtkliw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtdwwlloyr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtwodhzoky.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtconwjbdq.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtebascnwy.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtanzrwubj.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwhckunf.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtxmifpowk.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtywqzarkh.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtrzjezlqi.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuhgroudh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gteiqadyzb.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtxasdvdsj.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtjcwciiib.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gttmptxvls.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtyuqzrdey.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmzcmtejw.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtykqtjfto.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtqmauenof.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtctmigeoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtqathgwmj.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtlysobjic.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtfbbmkczp.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtlmtoxqns.html


<!-- 参考信息 -->