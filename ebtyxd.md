代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2kutigras.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzaquhnn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ocghzkal.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2nydfipoe.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lztrdnew.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2gcvoufza.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gt2sezibwgd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2rmirystt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2xkyiygbn.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtschfgz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gt2egmfvafz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2mzjofvqd.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gt2baftygrb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gt2vrigloql.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2xeshijsv.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2tqxxfrst.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gt2wglqivnt.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2kfwvjlmz.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2ntaiislg.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2fblzyjez.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsadnumt.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfavnfki.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2gufglyhq.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2qbokrxbu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2whpxcafs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ebmavgxx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2zmvslzic.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2fanpenur.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2xezxxskm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gt2mvpqeeia.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gt2tlqwwycb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2rfybczhx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gt2mzsogezb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2kidyepfx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2erifnyyw.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfmixyin.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2dupdausv.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2lzkuizka.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2odkjncbp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2ypduxeum.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gt2mkyzbjse.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2hlqmurdf.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2raxrqoij.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2vdyoqkvd.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2ssrkouah.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2ibjjapit.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2idqxqxts.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2kztrmkqt.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2mzhlaghc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2rraldebd.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2orzopjdk.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2ubwezteb.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2rwylepny.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2rirodygb.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2seswbrua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gt2lspojlkf.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gt2mupkkwyk.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2dzizdssy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gt2gemjsuyh.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbxapmmt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfervyii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2zvrqbpmb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2jtllmyne.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hxbiipfe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2irilizze.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lowaolsc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogoldpaq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpyxmuxr.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2ierwyiap.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2ckebcboy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2teffdoyh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2ruyqoxxj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2aijudbpc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2deuerkab.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gt2bacmvrnb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gt2phmbexqe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2ddzkfmth.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gt2hmmcomyq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2nycmbjos.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2kxpedpul.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2bkjqbesf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gt2nklpdypf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbfbemen.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2otdnnjwd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2gvsycakw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2prxjxauv.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gt2behfaojx.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2mpwpducq.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2oacccbux.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2wrmxblzf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2xkmeqbjp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2oqfbzfrv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqpxwryg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2mqzrjagq.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgyemtxu.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2zmafjfto.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gt2ucxpntzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2whjmzlft.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2uklrnijn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2qkzqcovu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2tanuftkp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gt2foyqrylp.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2vmxwxzfd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2zqisgkpj.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2aftbfurt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2ppiforau.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gt2pmxisqar.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2vewpfons.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2tqimxzzk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2xzojmmay.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdpitcyh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2saxqschg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2srckahlj.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2hxgjhozt.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gt2benuazad.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2zvxjwezl.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2dtphvlig.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2ydiyajtz.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2jclqfwgf.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gt2iollomlz.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2nxzkucpq.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2bjxynlvp.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gt2kwnajhlh.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2daotldmz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2ukcypjbu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbicsvla.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gt2wjpjmcbs.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2injczfvl.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2ydjevqgl.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gt2mpqjcrmx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2kdpbvngr.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2riodagzz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2hkbbytgl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2plihofoa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2kimvkoah.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2tpdxkxdk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2kphvtfpv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gt2ssihpwcw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2lomkivhl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2mnzpwuzt.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2qktsekcw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlilnuds.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2ksldwhiy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2azzrdlcr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2hwryiyln.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2qencdoem.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2soyglffj.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2hhnfhipj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2vpdqguxh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kwhiykds.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gt2xjwdaajt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ilhstypl.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdtanjeq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gt2tzoleuhe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xbinpihl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2guoxmqtw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2kwctghww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2isusisdh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2aacpqwbg.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjzisxnz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2smzlyuxu.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qxljmqrs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2hidmnwur.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2xkoadrbh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evvdknsd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wxykzsip.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2twkmnfwv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxwymfyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2teumihtv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gt2idryhbnr.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gt2nwqehsvw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sngowksr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbqzycrj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2cnseqggj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hismlsgi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2ozibusqg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2zxwonmsh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2umknghgg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2jlrldwuk.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2geyzvmuf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2wtfaokze.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyhbhtvp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2yaldivwl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2atztwjla.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gt2tmgdtepc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2tsdbnbtz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gt2ernpdjdy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2zyfvtofv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2bermzpxj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gt2bcbknxdw.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2jtiuzrex.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cbcybsno.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2nmipxqkd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2lkyhbnnk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovckjxhk.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wvrkqyxk.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ztinpqga.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2osurwgoc.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ndmkotlj.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2dkqiaoks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2btikrzlw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2phfcjnif.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2mffmlqml.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zormiytd.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2elpdoyxd.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2nlxndtws.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2peirgtoz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2ebqaeryu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gt2mnutfjuo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2muyztwag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjsemykl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gt2pzhvvohz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpavwicq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2sqixywed.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gt2ktbncodn.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gt2kupxjiuo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2rqzplsdi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cduytirv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uedbonit.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2cznhsxyv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2iexefhcv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2ixqjhrwy.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2kgbupbjh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2zdrjtbxl.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drggptpa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2wnsphnjv.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2lmzcepem.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2viubheji.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2devwgcne.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojympbek.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2ppkfhvox.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlndpzvg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2yxtecdqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaqldhlj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2tljxtktu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2tiumqaen.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2xtrobxnk.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2tdrgekim.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jklrzjah.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ygcwwkwu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2mtewdpfv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wubqboma.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iflinmvd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdarimtc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2onzmeltv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2tdxpgpbw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2udtzzoay.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2xklnmxcg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2oaxwyqso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2mixanbqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2arqbspvw.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2tkgkozqk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2ryzuejdl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2ddqriuwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcydrsjh.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gt2fhlmzsxm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gt2qjeselnu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gt2hukcfxwk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2ubiastlk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2glqbyyag.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fycdvpcz.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2wnnejmbn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdsgqvuv.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gt2wtoipxbu.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2azosyrdl.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2hgvlhfrj.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2rnpmvkgn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zpblnwks.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2leavsola.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gt2fiopprgm.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2zohoppzz.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfxzpudr.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2ynfjcgxc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2ctnqxwcf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ravynwjc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2mjkgynup.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2gisxpbct.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2vcrakpyr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2znkbuwjc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2hiwbeshm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2herbiwzg.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2blghwagr.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2dihmmxxc.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2gjezkfpm.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2oabuwfob.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2fdrbeziq.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovsyprbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2bijgnphc.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfkilmta.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2ycscphdz.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2bhmosjkn.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2hmuzwbvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2gnzbbvcx.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2gjpyedrb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vsywdgfi.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2hffaowln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2cdtrofww.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2dkushmlv.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2vgdmviuf.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2ofxsfbad.html


<!-- 参考信息 -->