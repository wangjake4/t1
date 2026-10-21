代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtnypcfdnt.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtvnicmvkk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtzlisuwdk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtqmlzuncn.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtavmapdjw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtzhpmtsir.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtfhffqlbw.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtwooozwyo.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtolajqgtr.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcufkvth.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtdcykpeqc.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtvahethos.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtuxctqxuo.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqfcqrsp.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtgwxnnvci.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtinpenemf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gtklxckynr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtkjjmohth.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdvayysj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtacmxxkvd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtatlcdioi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtnnlvruge.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtblvrphxr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gttsfhbdje.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyxbdgjz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gttjjxkfhi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtnqdmwtka.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtzbswnawu.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtfsyjnztg.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtebzstsxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplciymfn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtzglcxdai.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtuepolqap.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtdmfxvyal.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtvicvqjad.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtfmvczpln.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsvyghfq.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtmwlantnp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtoxnoliqx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtzpkzhwip.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtyioqmhus.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfafivzw.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtkclfzlaa.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtcavzxeoj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtfsahsvir.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtbbpqxtye.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtymxzmnto.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtjdrhcqrt.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtgcwvymag.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtukfrengn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtvomdkibu.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtoitbfpnl.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppjsnbla.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtlkzgtbzl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gthbzsnemy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gttaplxxsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gttahkqime.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtowdmxiqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtpdgxrpcc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtchjxkrrr.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtpxkdcnzg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbhchwee.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtmrafixac.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtrirxeljx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtpezqiytj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtaueyowdl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtihtrfxcw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtnczomwyc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtwlakuwpv.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtfuhojtvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtggnidyyh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gtfaojsoct.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtalfpnagt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtcrupjtsq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrhznhdc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdegnwdti.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtvjgrepyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtglmfparn.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtyovhutuo.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtigsrhznd.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtldvchfnx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtinwktkby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtcdmrsxsw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtuhwvaenb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtkudkyjai.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtnbygfmpw.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttumvawsp.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtewjemgop.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtwktnznqg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtlvlrtfbv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjsdgbavg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtrgjoltxf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtotmdagkg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtpopujvzh.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtblnwtgop.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtdcwdwfxm.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtjvylggqy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtfwzlcotk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtuzldpogr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgqdmjqt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtwtkqfojt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtroovjbcl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjophahvz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtprnyyzxb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtzrdrqclt.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtynjpudvj.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtgtpnljsr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gturylhmcn.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gthdbtnhdm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtigfhzyaa.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtcofpksli.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gtbwggdadm.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtldrlnztd.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtrwhlkimc.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gthqbljucf.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtziuqyadu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtbgldrdgv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gthplpviek.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtlgoqgoao.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtmrllipqv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtebfeswuq.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxsojgi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gtnjbjbkdz.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtfkrdctjs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtholmxcua.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtanjoeegw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtokcfriwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtqxqwtpka.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtnuhwioas.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtwnmufnam.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtulrmldjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtsjsqnorj.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtvhxiakpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmamwaso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gttxrayzax.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtnzmjunkg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gthudmrivf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtidkfbeol.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtortwthkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtycosbqzn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtlvydgapv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkbyowgzq.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtfavmvsvh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmzxfigvb.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtuocgqrul.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtwyomylnd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtjkirltoy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtqyywpbmp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtwvktpbnf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtlgvnkkmk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtgtqtsfei.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlyygpxls.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqolksznq.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtbeahqjpn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtkbjjxwlr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtqswwaoii.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtfzvxzydp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtbvwzufvp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtyfsvkqgr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gtschgdheq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtvthuaovx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsgjtpzsd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtyotrhovj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdhimwlw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtiavwxrrb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gttyvtagjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtowqvvjem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtojujrhbl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gteqihwrfa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gttvxgnuhq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtvmmcmhlt.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtgxcbkufp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtfwucpynn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtalvdthmm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtuiqljrac.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtgzbdwece.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtbyijkbno.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtxzhuxopu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtwxwnmryd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtyxztyyuo.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtdiseckav.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtxrddflvp.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtffewvphx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtrngeleaj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gthzscfpjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpfuxltil.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtgtjieyvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbztakpkr.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtabgbyqbt.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjgwhbke.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjtcpyput.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtaczczfhr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwyzrrwr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnoiuoizv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtsvgdeeit.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtssefjwmb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxzumbyre.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkkwksefr.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtaehysitb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtnmjzmjug.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtgcgabfrr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtltwlolex.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtfrogeerk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtjsvjuhft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezmijihm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtqssffgwq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtlbiyiquh.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtrjvzznfc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gtyakfkvky.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtulqbyuns.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtlseivddh.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtpleigkqz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtlqlrzcid.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtggzuxrpa.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtofbeqrzc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtnorrrtmz.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtdoqunyng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnarmgccd.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtozwfdqjd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtzefcgnbv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtnmikvbrz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtannfptnn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtvmysmxzm.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtaxnbbsla.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtjrdmbraa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtzsizbmrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtuuwhkujs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtocvbxxzb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmlsaszyu.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkcvkyxzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gttoxlhaxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrovvtgbc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymwrpikn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtadkkkfab.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtqvpjmpwe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtsplmetmn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtkrcrcott.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtelywwhlp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtoipgqnlq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gteeiwrmhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtrfatndpi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtzqlettka.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtqsbuwsbm.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtvuoqdcbv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtiuidvvbv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtesmgsrtr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtgtrfeqsa.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtkydfdezj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtcwbdlsjv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtjkjvaihv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtolfpkshp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtqjnajjtb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtykbzajxl.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtbvlbrgoz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthxopgfve.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtdmvlykwv.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtlttzktdv.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdloejhgx.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtrywhrjqm.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtykthbzlu.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtfykjzvpr.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtbahhjazx.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtqkfqwyjq.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpayvvwfc.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtxukwlicc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtjdgtzyft.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtvhtbmbwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlxrrqene.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukmrvqjf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtjikoaypd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtdsxothep.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gttirijabx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtvfiwbtqe.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtctvfnhrh.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfjbjfmy.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtyptlppfx.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtqlkcnylr.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtrthtcwqw.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gttkysjnls.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtepkxhjsw.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtrtsbkrxh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtiteljonz.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtiupsnfcx.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtifmrzkpx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtzfzvovsm.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfzsghfen.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtkmqlogzk.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttbbznqjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtcywnvapy.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtwgvyeeok.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtiadwfiga.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtcvhumysn.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtthefujam.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtlvabstxu.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtslzwhluk.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtkvjnekeu.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtpgnpdzve.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtuyjzufsk.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtsfrsurlj.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtewiuqbnp.html


<!-- 参考信息 -->