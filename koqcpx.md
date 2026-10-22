代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuyjpiwl.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtpxplsleg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtfukfezih.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtjkqjukvj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gtopfwjbph.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtgccfwsuy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtnphcnlnn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtedyjhldm.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtknretewm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtppdulfva.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtdezlgxve.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtjzaejtwo.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtwiyhntqr.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtcjvstoco.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtrvkukgiy.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtumlbtjpu.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtcvreetzp.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtrczxfcrn.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtpkjdmlow.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtqdeljykf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtwqanijxk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtkckzjzqr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtqxefytbn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtcwxlpyjb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gthxtoiiuh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtwyrofhfk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtofdxzywt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtadigyuaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtcjfqtfzz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gttsmvzyzm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtoughfqvi.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtoafnziqu.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtyvvpzxjw.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gthxrqyyrj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtklxydqsa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtjmjpxqxb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gthjcpmvdt.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtdezmjoxp.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtegzfaxrq.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtnurdvfra.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtwtihwjhu.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtzqxmdvfw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtwgcjynvo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtxbqapyto.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtxeqzueqm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gteqipfrnq.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtggkugafu.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtupuajqfp.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtqktqoktr.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtkleucljh.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtdfyzzyyn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtjhhdbboa.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtbzxvpgms.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtyaiccyld.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtvmhhlsny.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gtfzszibkh.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtkpvmgijs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtcnxvfuhn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtlhfkyriv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtkrrtqdbe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtarcfsrwq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtwhovxebt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtkawkrzqw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrbksowmm.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtttyckmyu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtyqjhudtc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtsfobyhfd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtilcmuswu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtwnlzgzfl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtpxsdxosu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtwrsbnejn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtrvgtmojm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtjgkfgtnv.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtparxkwvo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtskwaytha.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkuhydyx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtasbggqps.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtyegchzcw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtpflmdzib.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtibsqxhra.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtfzsfiisv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtgkbwepgz.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksblhnex.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtexsssyfo.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtsazpdswa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtutcefwmv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtviignxrh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gttlvbevns.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtejyxucef.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtqzwnhodh.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtlwhsvjvk.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtzokkyytk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtajspcamf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtkyxzadhy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtbxnnyzag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtqddoafia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gteatktbhd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtgeyevysa.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gteftnjhma.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegmdemmh.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxgbegycx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtxnzuzkmx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtxleitobg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtfxmpfrqb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtquqyhipr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtsjutqqkc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtwukxowri.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtkwkpchwc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gttibybiyz.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtjjodwkpj.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gttjdpdpjc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtogehadiu.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtxcixtiqc.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtjaybuolk.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtwwehirti.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtzoomvyzx.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtclknsdqy.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtlmcvmmfy.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvbezfqp.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcqsaylq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtoitkskqk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtvjvynghb.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtmyncmqbt.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtywwknxpg.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtuqracjcj.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtppoofooq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtnoimsbhd.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtdlbmtbfi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtwppmgxnv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtcyazzxqw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtpflnjsen.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtrcpybhol.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtwdibsjcv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtesptcqlg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtanrjzcak.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwhcnywqu.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtdmdpkxuj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtxpyrhcnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtiyedrgdf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtzpwxkuid.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktglahmj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtlmfvvkfw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtgnvxkwpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtavvjeycg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtepjdhtnr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlrhlblqj.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtmwiyeprd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxuycaqgm.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gthvmejtxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtlbmndrsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyzosuhaw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtfyqqqwtr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtrdleqyey.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtanalmbuc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtsdrsscxp.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtiskrdbmg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtmmadogrj.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtuvayuskn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtpmjxwlbi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtefaznhvr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefamvvcl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrwjzuhse.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhkdztad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtdwrepnns.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gthmgyirtj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtynkymkfq.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtwdqmystf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtfjtcucda.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtnrvyhmqs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtoilkmygf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtgvcldjad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtnytzuhly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtegqcntvw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtihjssxfs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtxtnsuskl.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtywxhisds.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtemjvocvk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtngxpisvk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtwmnbglfj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtcbgzhkwv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtmycxbxpi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfscqbuf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtgigywhhj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gteavjuefj.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtvhvkgvis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtitsstdvw.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvviyrbiq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtplwewaac.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttphpcmwu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtxniwijuf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtsklwgdqi.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtytrnkbaj.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnvvjgmzq.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtnwwasllp.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgkqrnhsj.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtrnqrpbgh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtnckgtddg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzvmdzznm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtcuuefysl.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmhqhsymx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtilzsjkbo.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtziydbiap.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtfbuxliaq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtizxcigjh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtfyhyccnt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtxofwlcuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpomymek.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gthawmdtsx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstaoylcn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtimlnemur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtsbcxdnpd.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtqmqtujsj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtknoukzrt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtlcnrdnij.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtwewrqomj.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtebwggcyr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtbagmthnh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtyihmgcjo.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtyitokbnx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtghcqkuea.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtssjitovk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxxgwffxu.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gthtsjehjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtafknvfef.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtpcfqfaaa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtrfvuokyc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtjxlicqop.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmlxaljwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtkvsrevqj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtewjqttuy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuofuzlrd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrycekrck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtunovdpnq.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkcxmnzkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtyfjdnbvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtjmwkorwo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdkkcwryw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmnvaahea.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtljntszfw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzuvzntsf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtszkbpqxf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtrblihqix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauoselyz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtqenszgur.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggzsyqjh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtphwdcwdj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtwdqktejs.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfogcstgf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtsehbqpwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtobqdcdjo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtesjcnxeg.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtbdnmcfuc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gttdyursms.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtyoepsdou.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtfynokpet.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvfoixpc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkjzopkih.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtgqmfgchg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtseqqbrrv.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtyfoqcrht.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtlajdfgon.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtgwqznbjr.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtrjvhslpc.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtwmvbliae.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqzayliur.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtlcdzfrpd.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtkckvlmbg.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtpbkqvuah.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtukbhpqec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtvvzbnfts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtxbeubmgc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfabwrbdr.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdhfknidd.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtriiynjcl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gthptwaird.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtooxsojrc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtshotwtkk.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtftxtksca.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtmargamfd.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtfczykaus.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtfrnjxaek.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtrrdgncaj.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtmwrapfwu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtzrwwpitn.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtyqcimelo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtnlcgwvzt.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtxvhfmtmk.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtmfzknrwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtvdhqziny.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtzsfasodn.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtdwbmqdvc.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtppcrnmsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtpuwlarsn.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtlisgufke.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtpmaamilw.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtklcnumgj.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcvofduf.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtmdfdqmvf.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtcmzdmbxi.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpymykwfu.html


<!-- 参考信息 -->