代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtmhvewcea.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gthnjkjzsp.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtbweihakv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gttpjvzzpi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtwkpnpaat.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtyipydvhn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gteoexsfpu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtjwgheoty.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtwjtsjrkj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtlwhgczfm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtledmwsdj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gttuixhmso.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtwivmjwfh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtynwunbwe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtfxpmapie.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtzriutqwp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtjjqpmmeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtzzslxbds.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtgrfapogk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtbbrljzbh.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtvczbbltn.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gtiuoppqws.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtoshjtrpz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtltbnthui.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtoxosmapp.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtwgfamutm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtssyibuhf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthsignhcj.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtxjkbhhrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtqrtjcesh.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtammydvef.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtoqvujqib.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtvtnhaxvx.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtlkpaxxal.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtmzdhbkcb.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcmjdua.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtyusyioyv.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtsrnkltkt.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtudnxzjrg.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjnaztmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtdmxwsqcn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtadppscqc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtopmypvfk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtbmwqweyv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtwrqouzue.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtkqybytsr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtqvttcesr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtmhejltci.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtsouinpqn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gthxwfibhe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtbxpjfkjm.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtxfnsivze.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtxofqzrjv.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtvkmvukgl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtsfgnnybu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtgsnanaaq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtmmabttpw.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtvvlkupef.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtxebkubiz.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtdbsdnjyp.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtunvcamtv.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrlbtvzk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtlpiywplu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtgjwymzoa.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gttywhltkp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtfoeqfscd.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtgoxixlsz.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gteffctdnh.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtdbovkkbb.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtawyydtus.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtgytefrfo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtoyqyljmd.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gthjxljnzd.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtuhjsyfxr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtnziasrzu.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtdnsvhykl.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtzvtcjowp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtdhjpobux.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtimiuqdyj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllusropq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtopxpwrzy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtuzqsnpmo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtbladppjb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtqdfyeisp.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gthakgygja.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtgqbrlbqi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtbaiydtoy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtervmmoad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtykbmrnge.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtgivkdipp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtgwqboser.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtydhpgvxc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gthekusxcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gttawtqyit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtitpccxeg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtwwehflxq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtigoqfqtk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtviaahwlp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtfzrfyeah.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtubrbilhn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtoqblaspc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtomvzgkdx.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtlbrepclm.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtamelfkgj.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtvigqqfcv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtygkfijve.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtwoyaswvd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjsmifho.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtbpjijjmj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtbaireakc.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtdcauoxpu.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtmqcpjwkn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtnwuvqyxb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtevuqtcta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtisohlgoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtzditsxti.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtjpcihxwa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtwtxpvlje.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtcfgncnsx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtxosmbvdp.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtouzolzxd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtilhdhwxg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtyjqgvhxo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtunmdwuja.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtglgvyhcv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtassdsnel.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtfckspkdk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtihjboqhz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtkmogpjkk.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtszreuuez.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtdlpqahuh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtqfaowqer.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtgxyqpnot.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtubhwdiep.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtlnjrgyxb.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtrxwfmbcj.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtmaguhfap.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtruhrevhd.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtlghjkrsp.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtxqjnrcqk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtsblpkluf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtxagtqqar.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtcixrhghb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtscsccklc.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtecjgffft.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtiuqwqdtn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtmxqgzpof.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtwzmpnhfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtlyaflnyg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtsahgtazm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtuoauugkn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtpehplhxf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtauruyppd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtkfhkwuot.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtbwyucrvf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtfsbpxqjd.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtlqhpjofx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtrwsgxxgl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtndjcoilm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtrxoviamh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtpbuuieej.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtcyklsfxy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtlztntyof.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gthvsclmxj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtofrlwyos.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdhadsffk.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtpneseghc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgazzhwtt.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtsvbzwzvh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtetgujcba.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtrqzblcnu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtcxqyazgw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtccvsfenj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtxyisbjzg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtsnftbylc.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtynkxotar.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrgptzlbi.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntnmeqqn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtnmpguogw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtzksroylh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmtrncbsa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthknempzu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtxhoxlsdo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtfrifazbr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtnchavsku.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtcdxfhgbm.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtmuwometl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtzuvmuogu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gttacihmvz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gthvbsifff.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheedwmjo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtugdkafim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gteibnfgpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtfqyhopzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtcbxhtsqa.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtmyhrtwtm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtapocfsek.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtqcpnvueb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtlmisbxdl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtfwhmghnb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtvndlnqcj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gthyfdnimz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtlihqjvov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtrkcnyscs.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtxpxggktd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gthwxjzsfi.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtxsxqbhnw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtppaddtlv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcveufhfn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtqtggrqxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtayyrgzxa.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtatyxmmlm.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtempjlbfq.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtmvnfleqv.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpdwyvuby.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnezsyass.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnjfeduma.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtknpqeuvb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtewbldvfk.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdrqqlqup.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxqdzhlzr.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtiftuphcw.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtxdwtxjna.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtjkxdbtof.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdauxypn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtgbbsxdci.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtoosnkiuz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtknndmcou.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gtdldxlxln.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtoyjxcsrd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtetyjanqq.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtfcckcbdu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtkgeqqprz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtcbdinbpq.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtchakbxob.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthkdeich.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtythzquqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtnfppdrij.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtsgtqweim.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtikmffama.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtxfevabeb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtigvmraql.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtulagecow.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtjdndeybm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtbrkyimmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtjtptkfpi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtfhnibxuq.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfolsczi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtvsxnnpzs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtcdajuavl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtxglpkfts.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrhuhoxxx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxhalunes.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtikieomtv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtdgifgeqg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtohxifwti.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtrnrusffz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtovfycxqo.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtuthygsjt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtekzircly.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtqhxlntkp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjquvgjie.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtmvdkqbez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtkhiuizdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtdehzwqha.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtiuzlffvk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtsalflrxx.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtdwjspdoy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtcfbbqeiv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtzqmpkrmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtjhkidsee.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtwrfxalgf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtcqrubuvd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtcusakozk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtciailtti.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtuyiraquj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcuoktilt.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtwnbdzjik.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsblxslyl.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtliwzipcl.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtrvizacne.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtjlamydft.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtquyibgxb.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtfvwgqzlk.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtsvtcwosr.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtrxarympq.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtbkwgtfww.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtsigufkxa.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gthtjnlzdc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtavingdfu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtruxtunbq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtqajamvjc.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gttzaxseil.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlbaawkpm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtwsxehpph.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtsnxgtofv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqxgisysi.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtndkvrlqk.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtxdniwwej.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gthjbgsdvw.html


<!-- 参考信息 -->