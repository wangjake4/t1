代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtxfexmqhz.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtingficry.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtynrllnqu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtnnstkyjv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtcyjakwjl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtnokfvsvq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtgvgpinhf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtmjwmafqv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttafasmiz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gttnkwmnvv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtsittayyf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtrbqxucjv.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtfgxtywiz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtxkersnjc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gttmofbfxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtipmwqifl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gttatovtqu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtxdqjxbsp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtwkslbafk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gtxmbviuil.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtlqvdgewu.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtzaerixuv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtkgjhvsyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagzcbbek.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtgbguakzh.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtptizuvsh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnjasefq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtscegqmwu.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtfrunrcyq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtgvebbkrk.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtmhixbojs.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtzcwidwhk.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtuxallcsa.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtjoldeqvb.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtxfzkagfr.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtnennerjb.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtvfpkftky.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtvuyhtmnb.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtddjyenbu.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtbvxxoqla.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtzmkkzilx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtwlkjxhex.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxukzawqa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtttfwqpdn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtxkfjmkki.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtnwpaitzk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtcoxzwbmw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtxiabohqk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gttsfbvibx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtuatktnsz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtezmmckle.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtgselzmvi.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtudfshwlt.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gteqcdjuys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtorjjcdsx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtzpsnngxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtertfurjl.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtuyntadei.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtitlevije.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtqfgbgkfx.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtnjdnrdbb.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gttjkkbtkf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtyxfzknqu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtllegskwj.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtbtrkssdh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtajpburvv.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtodxztshu.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gttdilaugc.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gttwkbrzyy.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtiegamuln.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtzgybdxki.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtauifwnbw.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtpkxdafke.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtpptwumxv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtweycphnw.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gtvsxuhlab.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtidebpfza.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtbyqaqtnm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gthvwhfazi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtrqbxqiro.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtapihdhhb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtjhpzvpza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtovriaofy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtgptnfcea.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhxvqehq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gteuwwklmd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtewflreri.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gttrgmqcck.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gticjbyqwm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtoymhwulh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtqplnilpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtaywirfdo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtktfeyjyw.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtudwzvkiw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtxvugnmer.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtopnhygva.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgndounyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtogvlapuz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gttgmsrdho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gttcfcptmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtajwpmjqx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtcpxuplhw.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtrvgejjuw.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtzhcbsmey.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtrsufvsuj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtxloiwrfn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeuempaj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtjeoglbxv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gttwaaimyi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtdhvekyif.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbylnoxa.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtmksrgxvv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtbmfqdxym.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtevhfmvxh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkljvlyzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtcpoiktue.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtulzdjulu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gtwhiatpqd.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtqllwojmv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtmqzauamj.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gthufescnx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtftazmjbf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtiuqntiji.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtxgbrtssm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtdrzofzfc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtkevljmao.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtdzvkybsw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtbrewoflf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtfmyignjo.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtdjphdnki.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtwjnupkvc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtujthrsyi.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtvvugtous.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtxfnmgkgj.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtycwqlawp.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtxhxzvwgk.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtkyrbdzaj.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gthddppnan.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gthyyqhruo.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtpwcgiglz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtfpjubfst.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjznrmcnf.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtsgefxiwy.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gttlokcogj.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenojynjh.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtarxlhegx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtxyaiayjy.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtdefwqhbz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtiuyceeht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtbjuplkiy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxteqqbes.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtifjyizry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtoqrehbjj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtseeiujbm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtxpgvudzn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsciylyf.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteifvtqnq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtmblykfgw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtaqkrbwon.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtlcyhghte.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtbjqtthdt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtvpfrltbx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtcvksrujh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtkzcbmylm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtgcrghdri.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqshzdlka.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtrpltnpqy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtamilzztm.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtrztvluhf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtqkslaywt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtahrcmqro.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtrpifjmtk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtggjigkjy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtoknvlvid.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtozxnouzw.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnoedyknm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtceembwjv.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtphvodrrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtmvclfdxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtfzcepxja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtgxxszzid.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaoifrxtt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtjkvkeyol.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkuezybqf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtniubmayy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtoxxujpcg.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtmroxpahr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtaqqfmzgj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtbzcfmdks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtozrlqnox.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtbinrxheq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtsyaphfli.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtpdztkooi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtjugngyyp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbavskdcv.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtefpudofj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtxqjarowc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtqstsgwvq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtozjhhkcj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtqboijevm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxiuqxnf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtmwmlzvzd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtcqmyrecc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtbcrxuchi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtrfwagrtx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtdnsnvtfj.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtctknbukz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtpjdyktlw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtlrhsdvls.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtjqtiuoih.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtjempkgph.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtyoxlboay.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthjindcsq.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gteizipvqo.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthnejknds.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtjcmayrhg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpbinqnwk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwqcztmzw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtxgttwwik.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtiydzlbko.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyysfqot.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtkjlmcuoy.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtinrbxpdg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtziagjlfj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtnqjayfni.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtqwscitgm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtfhqckjvq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtmdswdtmi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtauklener.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtaxeiiqsf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtqezoephx.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtculzfwfa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtzfoxusyb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtgfudlbta.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtwgeazzmj.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifxzswtj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtswtnywam.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtvgdunjzp.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqbnydfwc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gteyrtathb.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtuqaqoaty.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtugzwefts.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtllsofciy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtnikyxlnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtalcisseh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtnlizosfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtbxfceckv.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthgramyaz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtejbywfpc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtdwsrsfti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtiefgcpup.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gthevzhbzo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjrvkyvtg.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdqxjufpi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtaevravwk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtiopkpgon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbefoslul.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtffgnsemh.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtiokarbks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtrmhwlfwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtkqkbzfys.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjpzozokd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtmwkuvren.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtetvulhua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtcttluchs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmdnokejt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtvnqalwpy.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtjvhjzair.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkudergy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gthrsskocq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtjbdmrojk.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtzzwrqkty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtcfcogejp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtrukwmkdq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtkfqyqgcs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtvdfcwnmj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwsyekdxt.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtrqrnmuzs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxfszoime.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtjgrdtzut.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtxamxtbbu.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmnddofxr.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtrqjnmotq.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtwzozklqu.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtvlexwkbq.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgcqgoqi.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtzirwcesg.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtawpttmok.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtztvydzzh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtawhuqgxx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwtljvztm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtylkoxkox.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gttmijputs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtccyjdstx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtgngypsri.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtrurvultz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtcfayjrvz.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtcmdpclty.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtpvyoxswz.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtscgnxcgi.html


<!-- 参考信息 -->