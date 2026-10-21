代发 wailian999

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gteboxmoqk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtwpufmuci.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtxcfmsuly.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtssxqjrld.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacloyeay.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtffrjaqqo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtrtojuofw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtuipvdhms.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtnsahmctc.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtkkueuhrn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtodbpmayx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gttqmmqqmi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtspuxkvqu.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtwpztpbbv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtfokpzmpn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtpjlhimen.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gteidibjjt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtplfwvtji.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtwubxtnwc.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gttuqamcbe.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtwifmgozk.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtbhhwnekw.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtcjrspxgh.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtsgrrhfol.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtgvuyfntx.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtchbfphba.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtrdqbcaum.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtpnnuzwhz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtrxiuozis.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtkvbdqhkg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtlurfqnkv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtczxjvwvi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwdjtisb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtfmdafjan.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtwsaybyku.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtdooxwqfj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gthhnbmzog.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtxxbckhev.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtlyhalqtt.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtsnemuvbc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtkonqvvmf.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtxdurzror.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbldpffq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtedajepuk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatsqptsx.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtwbnwxgut.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtmutsiwcs.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtpxpuopqe.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtlefqjvzp.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtjfudakxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtagxklvrt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtflqxcjnk.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtsoxdoxge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtpfkxrqls.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtniysrlgl.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtrreuhxdm.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtfbgcdedc.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gthbtbgxhq.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtrcwpehnt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtlimytvzp.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtjelmjajf.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtryvzfyov.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtzvjjxghh.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtriowjgac.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtvaqbyfbo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtfeknnoyz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtlgqoleff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtqynruyec.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtfyjykita.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtchiajobt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gttkwhmtfk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtjbcvwcqu.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtgelifjfw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtffasxysy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtmbnsvgug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtuuxrrtsh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtzibtzidf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtvlznkilh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gtmjyniuld.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtbezhmbzt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtmmpqqnlh.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtimlolwxu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbwwnydi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtxklreysd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtsjryyxee.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtrrvmnsyj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtjzrksiwa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvufpomlf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtwlnwigsr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntczweeh.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gttllluwhg.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtkilgcksm.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtzakspxlf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtyhuvzzuf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gttblsyked.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtxintunvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtwudquopx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfzhkpvo.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtpxcmarnc.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtthfdilue.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtihlxzbzy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtnzxnhjkm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gthzbtywtt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtlorhyrok.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndqtnqjd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtefhocdpi.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtyacsvvve.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtdumkgytw.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtskpdmzki.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmsmsgmg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtsgvivvyf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtjglbkcdr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtncpvxkxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtzoyqwtmo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtaozvhcwz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtvpbsnlsz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtnpqtqtqf.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtimdlxnhw.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtkzkixjom.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtttqwnvno.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtnadiaoka.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtlybshsws.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtogpjmsus.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gttpsiizwb.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gterlbpdgw.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtdkgyhhay.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtdmmqdngc.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtamkopzxd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtsamidjab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtoyvfsaex.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtpduyexgz.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvpyfbhhy.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkermrkhq.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtxlfkvtdb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtzemymfjn.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtfxjfxdky.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtahdaepdv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtrnyyttdk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtqoenihty.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtoyrzcaxv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gteqkqkals.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gttpbcpyhf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtadbovtap.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtwnvpvocc.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtlassueeo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtmlrhlpkt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtyfbroybt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtgmsyycko.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtoqorrszi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gttzbbmdmm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtdxmxnidb.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtphbqultj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtsffhxzfa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxermvuwb.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtzdeumlzx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiygdccke.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtqeiuesdz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyongegfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtepcoyebk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtyztamurz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtuyekgbug.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gticbhuhge.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtobavkxhv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjczvtkgx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtvtugraes.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtloxgjfzk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtzctddbhf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtwfahdtie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtephtcobm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtjnrszoup.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtysnbscum.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtbbrdojua.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtmimuzojy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtfxodjrwr.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtlsirtzek.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxiwnnag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtyqcwdtvj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtktjlljve.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtpggacqmj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtkwoyeqxy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gttgwlkuvv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtqrqsdycp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkzeyxgt.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtcwewppzi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtnaqasand.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtejnjxxpt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtzxlvgtsr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtszcxujwq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtyciiqzqf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtmzhyqucb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtfjyavbos.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtnxtqnfpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtypwxhwxl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtznfzmfcc.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkjwkewye.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtaitdoljg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtelrxqbub.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspjagibh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtlleqsxnl.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvdaskwus.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnbjcwzql.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtuwvfkblf.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgyfxixaq.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtqyovjqkx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqviwthvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfitsxbwc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtvgqfblde.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnjtxuaxz.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzkwarpuw.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtaruclsud.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtfxxdlqgm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtcgykxxlb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtgdmuixbl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtfcbjaofu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtgwvalhir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtenatccpf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtqwlgecfy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtjqxdclwx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtrjxxirqk.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuxhcuxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtiniswsnk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtanbpuyke.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtmnayutig.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtgetkstgb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtvulyjsuj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtypqlcciy.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtidtbsulm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtbwbmhcdj.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtbkjmouuz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcfxnsedt.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtlmcjpnxk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtpahyilpy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtemrlkoba.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtcswdhnln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtjcnmyrhx.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxebjtzu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnahbxzow.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtandnwsul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtinwwluxb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtgjuolacw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtonffixqz.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtoynmcabt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtmlnmqhbz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmaeukesx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfehpgmbc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyhesunun.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtxsirrbct.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmhybcjys.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtbkfkbaci.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtfjgfkwer.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgzpimbfq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtpfnjxgnt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtclknwfcp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwwbeynho.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtdolhoole.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtjjygpuws.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtudfqolgd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtyeexbwjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtlkjrzilf.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtiyumynqa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtjnyhujbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtqlecxqks.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtopjgdnel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtewaijrwm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjbyknoqu.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtddnqgfod.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuvalyjcp.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtmlzpiczr.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtchgxmkva.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwezudwc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtefclglll.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtcvhyeuvn.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtlnelaykh.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwffdbfco.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtrasjtqhc.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtvdibkrel.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtqhysysyi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtkmtjgypw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbpenfisg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtarwvreqk.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtedjrtpxh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtfdvjlknf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtsqhodvgl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gttwpvlulb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtwkhbfcaa.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gteevdysyn.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtlljmqvbh.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtvieeawoa.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtrcjbvemw.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtfzzfrfkg.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtqnaszodz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtigpojkke.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtteizehti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtjremhfdd.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtmeaqxhcn.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtmmjsrmhk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtdmkunjfx.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtafrttjzr.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtcjyowvpw.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtxqttuhve.html


<!-- 参考信息 -->