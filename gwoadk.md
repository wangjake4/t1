代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtdbjctiga.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtiwgynizw.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtnxtjyfqq.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtnrwknykj.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtjceqgxvf.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtwxtvlncz.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtgcmlvaqm.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtwndaiupw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtrrtxdhbb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtpjrmqwzf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtaktrglsc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtwlinuvsl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtepgdnqml.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtrrwykmbk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtxqjlyqzh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtkyxvcxuj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtndvgczyh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtwasubsed.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtpfoffatr.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtfxvtdlnk.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtkldfpmlh.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gttlcwbkdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtclnhjjts.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtyqkotfba.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtposhdegv.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtjlcvauzz.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtefhcljzs.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtjqtuoaky.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtspknulwp.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtayzenhqs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtriyhfwvp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gttpdnfcdq.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtijahmgzj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtyauscflj.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtmmlnokou.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtxbglsjwg.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtsaayuyhj.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtlgkldecl.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtsunemlpb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtpykhgych.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtpuuatzbb.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtwskeeeaa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtlbeejtum.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtjztprddx.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtupqmfkky.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtegslutsj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtdbtfzjwi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtjxldfdyd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtfjrndmkg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtixpvtlhk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gttnqybmsu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtbvqoqhsr.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpnjdaao.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gtezspuohn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtgtkjxihr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtxjlivjvm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtkgyfoxoh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtjouvimbd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtoblocxlq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtcaccenvr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtozudgszs.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtbeqzvtha.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtikyhljnq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtigoligcd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtleurglyg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtwefobmsn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtuitsmfob.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtdjuwgxus.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtkflkjuqs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtowtegkkk.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtgriczavz.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtelioawcq.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtjwrzfolc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtugcfwumy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtwfrocfda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtdaliousf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtctdhvbus.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtpjqsmhpa.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtacuignpb.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtwocxtvsj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtqpofiyrl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtsvoaqlmb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtpktsgoze.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gteqpipkwc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtinhikdfh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtuloynovn.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtcudizoye.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtnhfbulpf.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtrtmtvuep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gtzvodkabb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtpmpgvplg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtlxovewyn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtaidlztcy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtqopjkqph.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtjifqyhoc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtdwumgqyr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtmlfivcqy.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaoapxud.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtiaosofyr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtbogggtzl.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtgbidummw.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtdbkuovii.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtzfkxstkw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtyrvxrscu.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtrlwheimy.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvyikofo.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtvrlhzald.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gttcrjmtzc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtgbzpiujc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gttameihpp.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtvravdntl.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtsertylgr.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpsrvnsvj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtjatdsmla.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtxngmbrwe.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtbbcuufhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcuetnxm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtwisqmtrt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtqyxvvtvy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gttorftfsg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtfhmiorju.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtdaxwihgo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtiqailxya.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtwdhcavvh.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gttbqqfvjk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtxxqrnzlh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtwgsqgszf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtlmvkklhu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtlwokwaqv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtmyraoqbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gtjieauiay.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtauzkjfks.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtxtgtzcpz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjsgmbpma.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtqeyaxzif.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdbfbrgag.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtbzwbqqes.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtaxkdqnbf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gttottdoxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtsgzdcoge.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtwbzdvaih.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtseobzhyl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqqyvica.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgknvqcj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrixixynq.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gteefjuzks.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gttxuvawan.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtkigxvjyj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuxcckoj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtgtdhhtwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtsjywiqny.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtsefzcbtm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtvfgmoion.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtgaikunbd.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtsoldybhd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtehrtkylv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtmthrotkn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtnvfjriye.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmnkunae.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtsfbitzkk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtgfgxxgmz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtohedrzhy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtpsyqomvk.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtvfrnjrcx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtchvsjtkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtzqglrqbe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtzhoyvqaj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtsfqrjvbw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gthhgaijgp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtdefvkzwv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtthlrfcox.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtwuinyjjz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexfymgkx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtnbuyfjre.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gthqerltxf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvobakvwa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtycaabzez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtvcatgkqp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gttmxzbiim.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtiowsnokr.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmuieyeyt.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtchwshgwm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyeqionnb.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gthgrjdoyz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpkommxeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtttnlxrfb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gthokstqdm.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdeejzsbr.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgwomifhj.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtdljvpgqg.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtmtnsbbhk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtvlyvhhrj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtppjgnlaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtieyrxokm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtrqgvbzzi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtdsuusvjo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gttrhqhvdq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gteamcwniy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtvfaidwem.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtvflohtpy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtemgopove.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmeoyabe.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtkvbjnquc.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtyxoynzxa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtkkzlndba.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtueakktys.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtyiejcscm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtophboyjz.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtemewexde.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkzezlrvb.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmpkfqpan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gthrdcecii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtmxbbcaqa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtzxurlhce.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtorxrulpr.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrdutsohi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtyohfdegv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtyhbtnbwp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqxvnklka.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtnozqyekh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjkbizbdw.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxunjoqou.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtdttfawvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtiuxugmvq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtktfhhwqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtawlwicws.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtwjnhqpxc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpxsxyind.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gthnmifxuf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaibrprzp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtkzehnhyn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzckjmbw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtyeeabuex.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjwgkoui.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtqhdnzcsp.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtqqrbpavc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtviwzzhnc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtabewlhui.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gthkaaermb.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtkxrwedmv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gthgrxjpgg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtgocwdowj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiduewzei.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gttnackern.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjquomdky.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtxkotpuij.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzsczbpsv.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtnrhthvec.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtzkvtnver.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtmxcpwxwb.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtkrdouwmg.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtvbadrmjl.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtdjfzoiot.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtdwzdxvzn.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtednknnwa.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtgdgifjym.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtbrpqpakq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtkgzcefkl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gtjnzukmec.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtfpjojtgm.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqodrcmu.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtjctsgmbb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtpizsilqg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtpuhlplxt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtekmrtmbb.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtykawjmmf.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtrexonhmg.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtrtdeamrg.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtqplnikjw.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtvgbhdqbr.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtijwtnvze.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtdbumsfji.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtaewqdknq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtmaoujnpa.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtxdgehezt.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtipnjdlbq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gttpdrzvnr.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtjnlpbdnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqiynzdwy.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtcchekvnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtrdrlpuuy.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtmicoxwea.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtjwgjziem.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtwcviarkq.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtdtldkcsw.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gttjnuuxvm.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtugpgsrbs.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgcbfourf.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtygsrktyg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtfrfzbqaw.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtduoipjwn.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtyatbaydf.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtdtnxjwrb.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtdkumwfzn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtdjkcsynw.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtvztdpfda.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtakwflwfe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gttptqfbmr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtnccgyxry.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtdqovqhat.html


<!-- 参考信息 -->