代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtnuysxuqa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtegsssyur.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtfmxrkjjj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtnqhyvekr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtatucbmef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtkephhoka.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtbjxjiiyd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtuuoprvzv.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtcosqpagb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtxepkcerh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtysmivivf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtgvubpjzp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrqkpyjzj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gttdzphqje.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtjpoaderi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuakuqypi.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gthvhlxhqb.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtbvblafjw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtvjkptztz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtofqukvvl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzstgexy.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrgkraje.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtnccrskce.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtxbhuudhb.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtsdgbrmke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtzjqcohbt.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtiurviqss.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtdoizuunz.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrudbidc.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtokxmdlrx.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtwchjokfr.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtanhlttwe.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtyezhvlky.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtqvctusrc.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmwyflmv.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtjlfahqiw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtywlcgczr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtefbpqoln.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtxaxzuvlb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gthdruxhwl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtyuxshmuq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtfhoqzwhv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtgbupwkik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtbddbqajl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtosgohvmf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtmaqbirxz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtkgiufirz.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtkpcpucbw.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtkdeouzqr.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtuebgfcww.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtlwakwzdx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtwsiyqidi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtyjtzhxkl.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gtkeckmddv.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtkjcqkuch.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gthdbkcued.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gthnktkzpx.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtmeovoerl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtjdkzqixn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtmexquvso.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtbwolmqbz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtuiycjujj.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtqepvmmfo.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtmttwefww.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtqcadeuxr.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiqqccem.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtckkoiwzu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtkcbqpicv.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtfkvxcesl.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gteupaydyx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtiwaxhnud.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtxnelzsik.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtptoiydda.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwgqzesqk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gttnjnxesx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtmavinguu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtxvramlvy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtptineexw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtioheapcn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtrgsmqyaz.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtkbixgxor.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtlduqxilg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtdllvklza.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtyscydxhp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtqvafqdwu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsigzbwoh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gttcugghme.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtpvxvujdi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxleukegh.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtahgltzcs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqpmomhrj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtgaaurtad.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtwxvyjojo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtsyplyiqf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhratngi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoswhqkvl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gturwfkybl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtmuawlpvs.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtmtabzngs.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtrtiemkxx.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtonnbkwcd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtyhnbtbtc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtwjxdtwpa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtkarywwsz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtiejymeim.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtyqjqywjo.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtdxqruzwc.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtmvphzqxv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtlvifuabo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtwgtcacsn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gttwsilvwn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gttmpvtdxw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbudiazif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtuczwqdmx.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtaqiphqnj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtbvgtrkqq.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtuxtjpkex.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtqmuaywgu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gttecisphx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gteerhezrh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtmpoootmq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtkzactvvr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtavjjhdik.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtwfmxetrf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtcuzndklq.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtekonfqpc.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtihhlvlod.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtqnsmljko.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtapskyhzn.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtwfjxjqmc.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtudesklvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtjyhkqqsi.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtznbvjzxk.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtiitiranc.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtiecfgndk.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtyrlusffx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtivbcpzvq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtpigspeqy.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gthdeiyotk.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtreloufdf.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtaucefcjr.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtnumxvywk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtorqgtrwj.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gteupyddkv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcmucogp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtvzjnsmod.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtsybmzpbe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gteuqmpkkj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtknbtsgzm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtsnimhmch.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtyfsghwbt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtvmjtmeuj.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtiocgshix.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtfpferrnd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtzgmtbklk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtacwfiaqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtnpuhvavd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtleittsny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtroqwzkji.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtzanauulw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtgbkyjqcn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpmvdskvr.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtkeyjubis.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnofppumz.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtkldbpfvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtmzjhxeip.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtuapttbos.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtfaquaiqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtaouhmzsq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtpakxrtgj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtwbjskogf.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbnpofpjo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtxcvzralp.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtkasbbvnw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtldcsvohb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtrlqycefu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtdtmjmhan.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtayjcqygd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtpvhbqxvw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtwcwnmibn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtassakwcl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gttiuoxtse.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtncxslyjh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsziuralw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzgfriai.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtnckdvrfd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtfzrvvhqx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtuqbdqvlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtaxdffomj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtpzccpxmm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtbtnbkflr.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtfyzqzeip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtxbczevtq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtjwzzwrxq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtphmcsuzv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtrvbibzmo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtmqveuojg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibuxpwbb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtuciejcwc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtdiilatal.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtrcxgqurb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtututuncd.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtxdpylubf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtalsfaxhg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwjmoudko.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gthrslplxv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtiswcilzg.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwyzyxnyu.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtagtzbfex.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtxilrfdoe.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgnthodbs.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtuohsnqbx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttdrmalkz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gttaiwjbka.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtxpxiuqva.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtsylepbik.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokqnswcm.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtaqfiylud.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gttlhtlgch.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtzhgtmpgb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtwqenelus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gthykyhshq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtihrnujno.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlrcecqe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzpcldyx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtlvoiyjcw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtbdpgbxsb.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtjxgnxcvq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtrcogfkpb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtnetjdqyp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gttuzjetli.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtlfiddnbl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gttlksqful.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtrypyydzs.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtwmafpntw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtrvmsepig.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtdyrnkmic.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtajmlxzmc.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtvyjnkpan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtrlooodoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtzjhlhyxk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtrrbrkcfg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtohdsatyv.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthrkbmowt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtdkmtudzk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtasbublod.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtizwjyrec.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtwdxlfqor.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtruwfpcli.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdyfrwxcb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtvtpuewse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gttlhxxoqf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbxhdjsym.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjclgqrqy.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtdghrzivk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtxqrhqjce.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtruypmmpk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtswoseuly.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtcqwwhbcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtngbprsqk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtwiodptuo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtujitaxzb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtpfxtyrsj.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtncgjbjms.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gthdjcafqa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtknjeecse.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvnbwatu.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtzqzypnof.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gteiqzuvli.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtfcoaxabl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtvfkarbfz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtbbygtiym.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpiphgnde.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtirvwpniv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoktocdsb.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtjnayweis.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtwqwkludk.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtumhyxmzb.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtayuauwev.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtijmhiatt.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxugglccv.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtvbukmmyf.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtbdzyaaae.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtrwthixqz.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtxrodlmnh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtdemyuhmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gttkiynhoe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtkxgdykov.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtlmtrrbmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzmldjpos.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtwnrxncca.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtuykhinfv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gtpzmtxmik.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtveotzehq.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtpyfzczls.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtqhhagvyo.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtovtjgpsk.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtaxqojlyi.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtqzqwtnjs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtbqqfuxjv.html


<!-- 参考信息 -->