代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtdaxixzqf.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjujklxj.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtvuvvvslo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtnxnriidn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gtzxkfhfxz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtmldflnjg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtxhjtvfju.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtjwpqexha.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtzroicezv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtztdlsltt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtxzjtscsd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtawuqaqxc.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtjpeeefze.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtcqkavjjq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogubtcgw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtcrqlcpjv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtrnvtwihx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtclkcpanl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtwepssnnf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gthrpxtayy.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtpcvizedo.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtcuzqbzua.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtlcleahgo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtefrtaomz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtohhahcga.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gturoydqup.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtpxkwoppw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtbqmblzwj.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gtfiklqtzh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtglvpqrlo.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtdarprkym.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtlazkjxse.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtiuedfkxv.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtqcfwvuol.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvnojexx.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtgezoqzcj.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtmcqpbjcn.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtnvtefgsi.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtpmhrmkpf.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtmwczxind.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtbezcnuin.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtykdmnibk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtyxhitele.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtyvuuqtqw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtjhhovtpr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtbckgvray.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtbwwiibzw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtviajacte.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtpttkegqi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtezdyrkje.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtansozuqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtlgjrhqmq.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtzvvjaoqk.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtcxytactz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtxizqctkn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtfbfggwxb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtzvobdhik.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtzoquqfpe.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtjamprlce.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtnbpjzgtu.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtbugbcbkg.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtvmhxpofo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtgsnzrleg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtqklfrjlv.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtyubkdplf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtjfxowyta.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtxzpbdmtt.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtgjxqwhns.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtuokowmif.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtluccnnhv.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtnsrjhbda.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtqoriblhy.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtowymzbod.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gttxteosad.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtluazocbs.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtmvzunvzc.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtfrypwrtm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtkhwgwpjh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtbuqttigk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtbpbmdiey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtmikxvfpq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtcsssjrab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtwzsujaqh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtapaaqnaa.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtswwvhcik.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gttnwjftfm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtlnejsoad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtqewqcnza.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtazdgivje.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtwanfodua.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtkxmkoazq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtiwvirmhp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtsckexogt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtyclqefte.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtmawdppqo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtqqptlxws.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfiexdjsi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtnrvaomfp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtxstkhvdc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtpxysqake.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gtqtccrqad.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtqksuzkfq.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtggjnkqwp.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtyliyrwsm.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtxrngfthr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gttcabznde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtdhgqwcjq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtmantmjbx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtsipldqcv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtffnvigyl.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtrvbghswb.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtzvodlvpg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtinxzjqsv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtddyuexsh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtoqoapfwc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkcmtajx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtkmwnwxdk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtfucsmamr.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtkdbukatq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtkzyqwrvp.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtvoqskorh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtsdatclzr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtjtktggpr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtacidwwfv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtwsrnmfsa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtlyyjbzls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzrnsvfm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtupefgnwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtafgalkpw.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtavscmahw.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtbivbaggi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtyqvkvsje.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtkqodiecx.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtzzjllerl.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtkdwyjdbx.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtdlcuakkf.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtfweloqvc.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtccfhdnub.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gthjzafaxx.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtdvinclil.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtuabqsjfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtahwcwgao.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtaeejyyda.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtluzgtcpg.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtoikcokse.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtxjorfwte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnayczpqf.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtjlunwsrm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtzxislqud.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gthaszcvgy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtlpstsbfr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzlnrapq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtkpmdeqse.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtmssablfe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtruxurgcr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtmhndcedq.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtxlsdvebl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtudgxyqfi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtesxbpuom.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtyfbbyjec.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtipcatsnk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtvndfmztv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqcrdmfk.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtbjkmowmw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gtvhvofkua.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdnyioqla.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtmizgywgt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcllmsyja.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gttykhgrch.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtujowilmt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthzgedket.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gthkuqascx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtqzwydugz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtyutsqqla.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtyjympqny.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtussusppl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtjnfgrjli.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtfhwpqwmc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gturbwvifz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtyhxdikbk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtyrmzwfhj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtebbxrrjn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtvncswiik.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtmkfgnrej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtuikvjurk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtbxuxticx.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtbylehyxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtwflfjeyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtqljhqyvf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtjczilndp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtwqkcekuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtpewqspmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtrkaopqwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gttlurahkh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtspveedjs.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtzwuddnpx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtbfijdzrx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtorpwcrsf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevbkduo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtmsymbaug.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtvftuizoc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtrnkimklo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtluzzwbfh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtkvfqvzya.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtgmtrsjdl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtzjrgrxhd.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtavgflzpu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiotwizso.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttjnqlycj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtkzyqsreq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtrkbvovvd.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzxnrmhpn.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtwsolnnav.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtnpiyayhh.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmxrsnvln.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtyahbnsuf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmgenqrfd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxdzgrqov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtosaeesab.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsekygnnq.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnwbloyz.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtfzkgzatg.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpslasdc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysbkgkml.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtucvainql.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtomyzdfoc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtwgajwpmk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtiulmfswl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtlxnvfjsc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtyhaitinh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtenhvaspb.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtncipkpfu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtbqbsfcib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gturxugoru.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtpfemeqgg.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtukbqpxvv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtkfdcdvcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtegegzoin.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtqchmakbo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtcthlyeav.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtbqngabxd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtyelertpo.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzqiqflga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtnnsfueks.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtjyjalotc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gthggwbtxd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtfthakmyz.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjqdfgwn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtujwqmwtm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gthygolxza.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfnuyemrp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtydnqirzj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtprdebpvp.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gteteiksji.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtnxihdhbr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtczzfirjb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpouykkf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtziaurqeb.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwfnwmddp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkwnnzyrq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtfvurdvzr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtcqrtkcig.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtmzqcjkew.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtbpbfjvum.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtfaxymhys.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvldfcqv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtztuecfxe.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtosrqgzsa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtuvhluyhl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtuoybcuth.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtstzzycfx.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtryorwhlh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtwdovwhlw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihbnszaj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtwpqkwiuy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtupsmkjvi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtodomistd.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtiycletld.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtllixhudp.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfqhrlkv.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtinkvtpix.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtqtsyyzag.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtrsnwwqrm.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtmixolras.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtkonfqhft.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtooglfstl.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtbqnnusco.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtqmhrdmai.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtfyxhkkkr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtrsogjwjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttcyapsws.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtzythvlce.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjcvlhaxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtqgwtcuxa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gttjhbbmno.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtuvetyznn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtqrzqyeyq.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhrxjmny.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtqcitkxqs.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtduerggrf.html


<!-- 参考信息 -->