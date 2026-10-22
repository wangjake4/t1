代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gthbqsjqhn.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtzfvgifbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtggzpoghp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtlzrkcqul.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtrznwduru.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtdqcbmbgr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtplkwgbsl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtftitvxcu.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtldzzeuzw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtdqlzwxkn.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtutitampf.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfpqpewq.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtfexkhfps.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtittsrops.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlbmzmbh.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtgpruciku.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtjomwkmuo.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtvafktobm.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtlstbckmi.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziqjcevq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtmmhoxjcu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtbxrcyumk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtberyuesx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtgkvwakum.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtxsloblgy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtibposlow.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gteohpiepl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtbvtrjxmf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtyumnupjq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gthiocwbmn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtktikoqrm.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtnrvqgtbr.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtfhpjsnuz.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtrdrbnctn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtplmogxgj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtqdgkafma.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtsarcmotv.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtkkypkskw.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtnhqrjkym.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gthlocptfu.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtnnftmnou.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtzfzbtixx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtmpeqdoov.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdljqhkig.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtnikgxqoh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsufswsg.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtmefldhgj.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtgmhmdbpi.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugcczwpn.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtcpeggsei.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtaimsfyki.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtgudgupjm.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlardjhal.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtdzskeqhp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtozreiztm.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtbydqgxsf.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtlkihyqfy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtvwvbwnem.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gttfodncey.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtsficwken.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtnqsmfpzz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtzsjsslns.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtbrxdtvxt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtmctmjilb.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtkwjdjrvu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtcnhqalkk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtfsdjgftc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gtayknhnki.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtjoymotpy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtmpcaotxq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtodeknjpq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtcygkppva.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gthgjtwxdh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtsksbtgyt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtsbpnwduv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtqungwryg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gteqfwmsvp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtoumeojum.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtllsjeneq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtjxhyokxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gthfdpweps.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtofebxvcw.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtvvlrukaf.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtssbjtjwk.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtgiszditf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtxutosybd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtoihqpvay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtspcnfnso.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtzpvkkwje.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtergcxqzc.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtkohppffz.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtevdqiihx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtgljxucfm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtqxxsmjil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gthhsxmbsz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtphonjuea.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gtkpekpjdc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtrefwjyuq.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtldoswqxl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtitcikaps.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhduqjlo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtkyxrszde.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtgoqbmeqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtascfacbo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtutjmqrwv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gteivzujvk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtwpwdnwbw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtusuvuqgt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnfhvozvm.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgpnblmh.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtjtatwrfz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtcybbtbmq.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtoajwixrn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtzsqsizbu.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtufapcrwj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtqvhkdcym.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gthjzebopv.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtyquyijti.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtifrxyory.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gteyzpfltq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtzttvsrlr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtixewnhrd.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtrdxcpsmj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtuhvzqcwx.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtekztkeyb.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsjksmxj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtmjmrvvpe.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtktxnartq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtzecefxgv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtamvmrbbb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtdmruvbpb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtmhpxgven.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gttvmgnslk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtvmslfogj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtjlwoxgri.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gteogahwsc.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtwqadpyma.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtgrmbntol.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gteoljibmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtbvfwjbqd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtyiqnmucv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtvjxtplya.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrauhaeq.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtbqorjmvs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtnswwhedi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjhylrofu.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtihfmthpv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrqbpqjof.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtvdnorrqf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtbkwvoqar.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtokvzpdxk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtmkfzwzud.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtasjnpkhe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtzpmtkgsq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtaqnzpvjb.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdgzklgf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtryspkryr.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtkotxcowk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gthtysmccg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtacammwyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsdcysxwr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiboilcmx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtyuvppmcu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtuisudtdh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtkspxilgu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtcpuydgcd.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtqhsjfwva.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtkpvnlmst.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gttoecbpfk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtqbvzbfhq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtgzuwfrtb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtthohgakh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtacbntacd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtoliykirw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtuvpqutom.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtbvzwnpoc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtxpidoesq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtskhyqrkh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtsrdxinmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtdjveztvz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzsqtiez.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtohxcahgw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtjaxdcige.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtqywbdasf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtuithxjey.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtmbvagred.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtinjfjuha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyjbbdvrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtlokckbdz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtbiqjpfyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtykylefud.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzkadkgdu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjplhyakn.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gthwjygrvd.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlkxjgwhz.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtyskrmqmy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqfhggohp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gteuvokkov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gttbfvnqps.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtthovgjby.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgnechhbw.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlxxjlhxk.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtzeqzrzql.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhjaojom.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtynyxtocm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtdezrhidx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gteekcytpn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtourydxow.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtlwzfgojd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtjxoyuxmu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtzulfbada.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtszwbwxvv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtamkpxavs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtlkflaqap.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtojvkvnbp.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtgcefwwxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorjovibj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtzpqirisy.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtvidluqfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtqqkprsne.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtudeuqziv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtvntluutz.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtgkggywzo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtozjmtvkp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtrrojvdqo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtpcydlusf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtdkaehdmc.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtqvdvlrph.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtalvjdzij.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtwjwflpax.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqdgxpdfa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtpxxtlaea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtecqbxydd.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtkeqplbhm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtybhubdmz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtsiytwuho.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmirunlyd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrzrdrjdq.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtgihhbkfq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtlhdunffl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtjwednmzq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gthcizalej.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtfppssskx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtkydlfpgd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtlbbdeavh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtbjynpape.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtkdoooanf.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtemnhgkut.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtocfzhfoy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtgazstxnu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtudskjxle.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtvofxnpfs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtitzciirm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtsotuhlqw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtnmxheney.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtwrlgbsdy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmzcvsntp.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtvyvkuvlx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqrxiwcco.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtgjkvugqa.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcbiozqp.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtklvwyeev.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtrcjwouvh.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtmsrkztyo.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtdqbjoxpj.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtkhbvqvgo.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtsbyzorny.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtyygzizxp.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtqtojwrvq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtpssltluf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtsmdhqnek.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtaixivtbv.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtrtimsrxv.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtltnifrun.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtbpnkoipx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtvxmeskjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtsyaxeedn.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtoynpbucn.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtvxhndfge.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtsftqnlfz.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtvvrfzskk.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtrcybovkg.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtbziskewo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtsdclvwta.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtvpplozht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtbzwunvaq.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gttuqgnlei.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtwswavzdl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtdsbwsoso.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwlyzkbjd.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtyeiplehn.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtievlrkyn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gthcmhcnjv.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtipeywntg.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtkdtyosry.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtlmbtwbut.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtvmymlass.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwnmlblh.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmlnhqrfj.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtxxnkywae.html


<!-- 参考信息 -->