代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtygcthkgm.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtewcrsxnf.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtjikwvfhl.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtildaqfqi.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtojknuukh.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtssqrhfoi.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtbhqhosvz.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtcrrhdrbo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtylqrycxj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtxrmkbtra.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtukpavmjx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtzhralyjh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtyvamswqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtordgrqkx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtafpkvghl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtdjglsatj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtrptymcbm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtuadvzhko.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtqjiuucjj.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtapxmnjjb.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtvaldlzmi.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprmyuhcu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtfxyftkdz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtrtdvhdlp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtlyqzklwd.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgvzhvrew.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtmvvwougy.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwrpdtzwn.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtywsnriye.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtylhzsfzf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gttjnzvdfb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxdamdeh.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtyfcepycm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtxsuccwau.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtsdwqiveh.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtgvielafi.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtkzfhardj.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtctbnkmvh.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gthygdwvoz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtdlmfzrns.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gttoundtsz.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtzhksnbgr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtiprplfyn.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtpnhlidbl.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtkjzxlrff.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvhdtmho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtxsabrtff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gthbfzfptg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtgutelgst.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqgqmcpq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbivfkny.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtxuebhxqj.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtkccmsupp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtslrdhlgj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtcbeiroeb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtpbfeqdja.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtdqeljeyk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtlvzmzfrc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtrewhqyld.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtlfqwwvak.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtrxbldgha.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtukyqadkg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtiergftyx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtqisjzvfs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtqbciphxa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gthkaealkx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtkiuzygwy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtybsuiuqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtybmzkwhx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtskblmrzd.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtqdcteyip.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtfmfdxjmt.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtuhwjzfwg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtimgnvugm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtbypnvrcn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtxovmfpef.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtfwkivwll.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtvhcolzqf.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtgrqgzmui.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtwevmcbyn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtpstxwxyp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtvbanlasc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbfisyoao.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtyqcnhyow.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtoscpimfk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gterrdfrpc.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtvhvjqwaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gteaduflfa.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtzyjqjndx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtrbyakkbr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtvbbfnhrh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzddzmyt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtntclehcg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtgeftcvit.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtnhhajwyv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtagykqevm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtpvezgtpu.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtxipfiqsi.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtucuhsgph.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqrqckysa.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtetfijgkb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gthchiqeqg.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtxdutusbk.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpinidmq.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtthlgsqqo.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gteldoybnk.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gtgliskxwg.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtapddksox.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtezsnczjv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtaebhhpbn.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gttmryklfn.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtdvnpwklz.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gtarxyjxuu.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtjtvwumhc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtdrmpnwaf.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtlfpfhszm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gthmorexgd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtsabbxani.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtuwsmrtjt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtzewxgxlj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfckutvsk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtnvunmphg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtojgdiola.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtzupbylhp.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtgouuvunb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gttshehjem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtfirkwpib.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtrzxpekvy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtpjovnzpl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtctuwqikg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtzfrqjpan.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtljcrlwpa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtxauiatvr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzptuymqd.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gthluptrcj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtinbhsfvs.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwzucoswd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtyegcrbvt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknbcxzdf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtijxrutsx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtoytkltsn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtpjbashnv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtksroazzw.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtulkponhl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtrmzqqvai.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gthckbgybh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtxrqyevrh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gthchzqpxk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtvrwslzis.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtuxiwxjdd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtrsusjqwz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtsgcvwvvj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtbzezofeq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtqzcavuzw.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtstocwjyw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtkcfriraf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtwikqaiki.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtltismdrg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtnftzfhey.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtcztjztmu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtebuxmmuz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtaupppesn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtdkiapwcd.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtlexdjkjr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtsqdaiqzl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtwvmswkse.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtqbfuvsoq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtjbszskof.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtttxprcos.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtpdoytpgu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtqetgaswu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwqnjsmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtnpjtfbga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtxxdecvck.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvvmyiqke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrcrdgpsv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtikofqzeq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtcnebbcut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtbpjlowek.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtheufdksc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtggevmnou.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtgvjnrbso.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcowrrcce.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtsakhupmt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqvfcftqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtykhlhlcu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjspmikkf.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtshaoixku.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtniwfguat.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtylyetozx.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtsevegxeu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtqibvhixq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtticvikpt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtuwomqitg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtyiwjeqgl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtkymjqjvb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gtilcgygkf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtnmojbcto.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtqtxhnxhv.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtetkhoxrm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtrqjwzwvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtitaqiqep.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtpotlfrgc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtllcqpemn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtvhstykkb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtshvtyqau.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtipncdecw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gttlutcano.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtcjonmeic.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzrczfwok.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtprddpwaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtmmbkfswm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtdmojfidy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhdaiyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gttdmcfmkw.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjvdfdhxp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtfazdipto.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtuqxafvxi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtzucusjdi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtdvshfjmp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtsvhgnobo.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsohhpncr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gthnvtrfus.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtbybwjacn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbpqhqcpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuqotqycx.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtjvdoniwz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gttcidgfvr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtpjcecfjq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwgtkzvml.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpgngeani.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtippmceuq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtbvlbqrrf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gttafyzxqv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtrdjbukov.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtkvpeyofl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtxndgrlld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtlybqkoks.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtiyfpmsnw.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gttauepvnt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtwvwqbmog.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gthxbhmuoz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtkaeehbfe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtofwnqhsp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtarjiriqk.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtzwirlblp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoxseuosw.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtsdhpzpvn.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtpwrhsjqp.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtwujadazx.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtwtmawqbu.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtblcmklkl.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gthhuzkush.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtszwtacun.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtlwyinjcy.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gthbnubrcb.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gthqacdamk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtctdowywd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtgirlzgoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtlmmtrvuq.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtvsnykxui.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtrgvnqyhg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtyfxarwqb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gttcipfwms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtdogwonnw.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtqosxbyxq.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtwwibxacn.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtiervxrzf.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gttxmlgeqh.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtlkmsecuz.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtgidmiegi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtykgharam.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpqckubc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtpdkndzkm.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtgfxdkghr.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtniczefrp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtggnggzer.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtvsfeoggs.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgivjtgrm.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxgrchqar.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtsgfijtkg.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtshvihluq.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gtjgxlrnny.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtgjafxrrf.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtfnjadmyp.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyptkojlb.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtzzxqayku.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtpfjbqgpq.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtixyrstej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtydjrfwtk.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtbcovvbjj.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gturrrlkqa.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtedljcwoi.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gthqnkozvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtcctyowxf.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gttcmzggsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtasbcnubn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtxqtukroj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtfhfkfzcu.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtsrbkhxei.html


<!-- 参考信息 -->