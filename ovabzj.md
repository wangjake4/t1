代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtdvyhfalz.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtjsgjtlot.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtjdxtuaqu.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtdhnmbtjk.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gttjnwcaim.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtvmxvlytk.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtqumpdnsg.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtsiepsbla.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrddjvkfq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtyxxqeqhi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtkdkiiqgd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtnkjgnxzr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtajpcppzn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtkhmuluae.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtosdxotjm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtsbzcbfwq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtlawdieow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtcznvtzfm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gteapytbqo.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtpkrbqaff.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtazesunla.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtbgpgjsas.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtyrhnfege.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtspztkbpl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtrselwwwf.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gttwfuawvh.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtmqvfvaoh.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtustpwsgn.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gthgwqxawo.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtovafxnls.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtqffiacpz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtkzyboias.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtdkanqtgi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtbmyzmvdr.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtxfavqyin.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtqgayfrrd.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gttxwarrqq.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtknlatdpb.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtdiregrdy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtxdxtryxp.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtmevtzqir.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gthbnbvrxk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtglrerlyn.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtjdntxvtv.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtwghfcymx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtntoijmxb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdfnlql.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtfdnwilhf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtltrlykfc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtiyxivruj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gtrnfdlzzq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtgmmxmhmq.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtaxsxowzg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagviqvrh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvgkkkvbj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtbgreoujh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtkdvzwhzg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavpsibsf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtyctbfzkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtmuytljzv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtdgjzxpuv.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtwbsopvhz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gthiqqjkrj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtccjtnybr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtyegamwje.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtmltiyxpm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtcuqpdtcp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtwcarbitn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtmlrlznpu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtsrjcamfh.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtqyluzxkd.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjdwstvar.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtkaceabqo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtdtngigiz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppjbfpak.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtixajuwvr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gthmjvxxsl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtycwbkaia.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtfgfslazl.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtxzdtrosa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtaqcaturb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtxfoqzjim.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtgmtdlzfb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtsseaphvj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmqbzycu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumlrsrcx.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtjhazvqiu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtprugofop.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtuwleteor.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtgdzmluvk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gteixslyqn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdidhgesr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtococqbcd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtnbxxfmxr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gteoilcpgm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtdyagkxis.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtmnpzuiwt.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gthfncxqmr.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtbeimdqcv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtokdwfmhq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtnegczthv.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtatdusaxn.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gterojmlrd.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtmhqzdpbw.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtwfjaztds.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtrfmqtaql.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtnnlbpxfb.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtxcrgxrxs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gteayeuzqg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtkxffppbl.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtioswezho.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtubsbzfxk.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtdvzyhjdb.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gttihjyucs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gttkibulbd.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtmjllukcf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtpqovwvqr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gthfsmapzm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtrscvrwwa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtgzzdnkuo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtlzlixwqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtdqbmztmi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gttxczkcwq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkujcsxrl.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gttqqaesak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtrhyehsgn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtxbwmpzfx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtpksrcfsp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtbkbejdli.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtkdwxqrgb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtwnzunxkt.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtaiyuqitx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtkmmnrnnz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttbmitgvl.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtsqryhwpa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmfwcbixk.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtfvznidtp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtxvokydzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdivlepn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gttmrfxpbm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gthplwdyuu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gttluddksy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtetkcvrpj.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjiostwll.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtffypcfud.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtcjlkoetr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtbfpuxjmu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtwbalgjoq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtchtsbjla.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxjdrkxo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gttiwawssz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtzmbgeocu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtufmpgkmq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtojeidabw.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtgijzgiuy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtqudaltfp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtnpvxzelp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtqxwvzyyo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtbqurlnjx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtjyvqwmsc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtvqvydevi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtkcykaoeo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtnjymlqzi.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtywqixdny.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtpekejhen.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtfgdqlmuw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtlxtzcqzj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtsgnehzsl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgclepdx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtgpkqhgdu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtaisbztvg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtilasfqad.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtogbvxqsf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtcxnawtmm.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gttylqlnav.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrycrvarm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gteskvhjcu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtzudbzizo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtfggerkhv.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtzzsevdpg.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdbysudmj.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtajjvrrpa.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaaapsvh.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtuhionmvm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtolzpurer.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtanzhhric.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtnrjlcq.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwprudupu.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpxvavnjp.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtlhhtczgp.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtobytcwqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtfkugajck.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtiisajwkc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtirezhwci.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtrslzvqre.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtgddgoxqa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtsqgjckeq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtakwgvhbv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsbhhues.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtzjvhxvhg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtahhagkml.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtkqwnizeh.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtdvhruyde.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gteuhbviwq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtayopknnv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtlvlobgnf.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gthfkbwtsz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtzhemxqqm.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gteklizaea.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtkgazdzem.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrlmnckha.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbzrzhxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbqqtpiv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtqmztnjke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtpcqxtkdq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsfknqdfw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtseqzmawt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixazlqiz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjbyeausg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdkozoaxr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzdffssqw.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrfovudo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtdiuretml.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtnguraswy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyvvfyitl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfojldwck.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtboczpsjw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtugmjdsbb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtwbawsmwj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtouoslboa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtzslhwgnd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtlegpdsxl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtfgtpcfgo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtfrjqdinb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtthqhtftb.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtghlrcc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtinmswewl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmozxejhh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtzkdqlgwt.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtcvwvljvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtvhlsbspo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtkrsokfgh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtekfrtfps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtsylnfwkq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtivikxipp.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gteyzbdypt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtshsacdnr.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtpyeciltb.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtarhbdfus.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtimrmqeym.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gthllajdbv.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtidlwtznx.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtpjpnhkbt.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtbuthwngp.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtjltoebvi.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtkoqdkkju.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtyvmeasts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtnbixjmuk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtihvliols.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtuloliwaj.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuzqlubrh.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gthuanxprs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaejqrepn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrrvkmfmo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpgbmkjte.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtatcbltok.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtmmwnvtkf.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtbklymsgr.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtaakqrknl.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtfvmxisnw.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtsqrzpreq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtxiytexlf.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtwwrmbiuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gthqutskbp.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gttadkcbdo.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtbpnshkwl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gttoqhnkvq.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwvuqtmjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtcyaaaycg.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxipgwxnf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtozublnlo.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtddtfzuuy.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtuopdkagp.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtrycijekq.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtbgqvnoof.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gthudtidwk.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtzforyimf.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtqaljhwlp.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtexkujcqw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtmtkupprq.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfvzvgdy.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtefqgrrqm.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtvuyyxnzq.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gthobywglu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtnhuradso.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtmcmjpghn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtydgwtdav.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtwfkrsfri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtjryagejl.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtzbeupjgw.html


<!-- 参考信息 -->