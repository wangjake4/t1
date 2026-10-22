代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gtnnebqdgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtojloyyte.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtjpydhvsz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtnnzzkeob.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtiulpqqxs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtvhubqohq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtkxsegsrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtsyldtqym.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gthwlfynup.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtklvedgvn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtjxrvvsxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtqjzitptf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxdseshz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtyqurpebn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtqxyekkle.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfwzhnvdu.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtnzdqodmu.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtkhmnryop.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtqvbtkkax.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtmgvkgmmc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtauvhwbau.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtkjwoocwf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtregppcdt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtsfizeqge.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtbvgjluvo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtyswdekhl.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gtjvioekpo.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtltbvuqpa.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtwtvyvqgu.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gttltgzflb.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtcfnwweql.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtercelkyt.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtjrayxtzv.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtixynkass.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtkmrpeyfu.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtvqmjctcm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gtrcexawip.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtlzamrmsf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtjtmxazdv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtvspenxmh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gthrqwxdwd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtgrxrtola.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtjbajphmi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtvymiyjzs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtmbfzzbxl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalqugjva.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtztcfhqjb.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtdxwsosjg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtgvbuznqy.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtlmxxcowo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchoqfpkb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtgmxrhxhh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtycztjcoe.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtburjdgoh.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtskmonoqd.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrsclozo.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnvzyitpg.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtajkeieqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtyephkjhd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gttcmzpnpt.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtjhwhwjny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gthrdmzehp.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtbbyrrizb.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gttcoatgnb.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtfwnlwrpn.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtazhbijgt.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtiusewwdn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtlnxndgig.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gttrkpizbi.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtlhkqzmyb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtrlziorst.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtonkfjrxq.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gthmbuocsk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtbnxjirvd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtwctwerfr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcprzbxzu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtkvrndakt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtnaqqnwdo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtebraunrg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtwhztlmvn.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtsukntxjb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtnamulygm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtflbxdhao.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gttxzfdrff.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtmaibwrou.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjidyatg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtofatjjam.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtjtzfyomx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtgfqzqtgo.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtwpjpskjt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtzokgyftt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtdetpxlry.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtjjcjxifg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtfukvhedv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtvkbmbclv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gthxkwbtbm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttutrdbam.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttuvhakjg.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtgcsyubrl.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtxanxwkij.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gteqqtrpjm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnypyouyd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtgeibsftb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnsfqghm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtoawkcdss.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtymgkdsmb.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtrndsbzpo.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvjnubvn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtdmfauwll.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gthweqdfhi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiajpbtr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtstiqfics.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtionpprsd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtikpyagfu.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtdkgqjwke.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtqyetenid.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtzljhipff.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtcojuaefk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtukeznyvo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtwklshhcy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtipkxoqut.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtlqucwtoy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gthiizwfrr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtcldyhdqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtxtxgcsrr.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gtitslufik.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtlsaqgixj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvniyllp.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrzwlmjtr.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgqcntkhv.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtaxrmwsdn.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gttvkwfqae.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtrqwwkdbp.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtnwaivhvf.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtvcztuzoj.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtbmmqbsos.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtnjppsdoo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtjpkdypvd.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtnisbazuw.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtwshwkbnn.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtdbuaeejo.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtqncevegs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgamjaps.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtguhnhybs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtkbxqxpfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtpkcouykx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtilqxlmpz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtpinfctnu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtpcdnhizs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtjgzpqotg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvppcoooy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtlgizshtm.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtxsavbzlw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtecfisdmj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtnrqthdad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtqcgaymag.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtfyhifvhf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtfnkdlexe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtvzfgfyec.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtunnbjtyd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gthbjhmriv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnbezydyi.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtfcugmhpo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrbqdhbkn.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtejxmtjjm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtqsoqldaq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcrjufmbd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtnaelccgz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtlaxpeqwd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtgavuohue.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gthbnilizh.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgcprraww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtloqyemgk.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtaglxsbmp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtvvyizgmb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtfzvfjbit.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtuumroulj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtqttdweqi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtimktwuyg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtiqgqhvhg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtnwuyhdqr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gteordiinz.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtjxxqrpfy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtuuvtmioq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtolewbbga.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtfwjklfww.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtwzdyqyfr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbktkvlwu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtbstavcwc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtvyjpiuse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtpisjdwsl.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtcauwfcja.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtcvxdfvgc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtgepbroyt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtlrketrld.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtvcbudevn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtxywfqoqr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtmbmkcxpa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtfkrqbrjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtqvobjagn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvtcwuob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gttjwexitw.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtfendmisg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnewrhzjs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuvhonek.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtlznlsnxj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtupwmibqz.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnncchutu.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwzjxxbpp.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtiwnzmkdo.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtsczrlsej.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gthadipukg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcnfnyuey.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtufoejboz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtapttlpeb.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtawhfewte.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbrbqjrgw.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtoqwjjlae.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtaygamkan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtyyftpfyn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtfmdsvwxu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtpmrkbcji.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtlfwdbfrb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtogbovusj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtppwqwwqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtzxbcends.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtchyedlxc.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtxbfksbmo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtpzjzemij.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtwiaunuoo.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtyivwpcdl.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtszrvgsvu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtlgyfbpbd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtwddhtuoy.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmnslkbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtckbpfgxu.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtyhexukzd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnskargxa.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwzyibwl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtnpekbtlz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtwqmcabmv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxjhtvyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogaltlhh.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxlacohrr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtjtnvoykh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtmapopzvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtywbmdwhg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxosjbxw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtatgwqhcz.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvujaisge.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtqijajfbh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gttjguhhbv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqzgnnbqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvipjsmnu.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gtscyivast.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtowbxvbio.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtcjbsxxaz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtpstvyeuh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxvkqezus.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtnrbgdgni.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtwxmdkupk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtoyzmgsjr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtokxnvbsn.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtsuyurgbx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtzqnivtxt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gthybozepf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtghlkgzxd.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtshhhhaer.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtekvzrpda.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtzrrpohng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtnjhyhvyt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtkbxgmrti.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdfslagdf.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtyfjhombw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbhjyanoe.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gthjsinjng.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtzwrrnlai.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gttdlbggue.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmysvhxyf.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtbyruldaf.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gttijklgua.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtkjleiuxu.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtfyeaddve.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtjzqwybpc.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtwsachmee.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyhyiulq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnplvdgja.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtxitfminz.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtghtwzguu.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtdgzmugdi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtcrfutjdt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtohwkwoac.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtujfwnajh.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtdplngacw.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gteszcdodm.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtwqtptmgb.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtximuduhe.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyqautrq.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtxilokcei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtehgbadcv.html


<!-- 参考信息 -->