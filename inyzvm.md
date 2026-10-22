代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtywjcmxwn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtluybfrxl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtnkisnxwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtermudten.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtjygmgopf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gtciamtbcr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtwdmbdche.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtqktnpixr.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gttanlsnnm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtuykdpbot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtxfhmdcsa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtmkulvibi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtjkfpkwhx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gttrxlqzme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfujjyjs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtqwegdihl.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtuuixkpyn.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtyhzbpehb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtrzayjbbm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gthbvkxlck.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtpvdmjfqw.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtowajqtyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gttjlkvohi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gtyaubqexv.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gthwbmmtia.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gttryrjxwn.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtwuwtcyge.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtrobnetsv.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtrbyzkczl.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtgdkfjbuc.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixpphhrv.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtqizfblkj.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtnqtqitvi.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gteyalihjo.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqweuguae.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtvzvmolrs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtdviepwjz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gttbfhpjzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtlmnaksmv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtacgrvpqa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtjcfjkfwy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtxysbsyxd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtoytxsroz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gteiecjili.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtmqcubdhl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtycixsxlp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtlievubzi.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtdutnaces.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtaayllwie.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtkvdfachf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtsqdhtuje.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtjsfzbjlp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtrbudgrcj.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtewzjqzsh.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtdenktdyx.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtzwvgloit.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtzcxcaxoi.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtzgnvpanq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtdcfbwqer.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtfhbxovqj.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtznahvtzx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtqwgfvzyu.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtveiewyec.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gturanbntu.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtbjfjvgae.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtxcqrbpby.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtvukzbirl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtigysziqg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtgfxnojxb.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqokgzxzm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtoxcivnzs.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtdotfbnqp.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gthjpvokmf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtxdexavke.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtodeidghh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtnrpruvzb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gthsoxbivv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtnsmqtqls.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtwyiwjnnq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtychkpcts.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtwobzgqgp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtfoczshes.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtbujdzkzm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtgsluzthe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gttbntndeq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtiquyuzol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtzlryyxkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtoflzmnwm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gthauxpodh.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtljkclfhq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtaerjljex.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtkafdiipk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtobephomy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtmtgyugwc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtzqwwvurl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtpkepwolq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtcbuzosrn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtskcrxfwr.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtemqgewui.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtghvwfmkb.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gttuaytfaq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtkfuhxgoh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtktdqaxsz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtenivglif.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtzwejupmn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtmoqtbxrv.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtvijmxqal.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gthguypeqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtznqgrylj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtdveyupbs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtzxbkfgfl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtkfripifq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtunzdtexn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtglqirdnm.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtqpuwzhfy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtndyhwotz.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtjvtfdkvs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtobyeafmg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtznmoezrh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtqrwzifnd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtptxloysp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtziggrttn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtvqqpncdu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtihwwztiv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gthoczqxzx.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtebuyetbz.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtdzzokmtd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxozmvocq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtbuwcwcee.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtngxscygz.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtrxxueclh.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtmpsoqbep.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtzcvypcpo.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtdjalppem.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrvobyhu.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtvqmfvqnc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtivrvaztg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gthbqmcftc.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtitkgwkoa.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtxnfzpnuj.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtghqisnvx.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtcsofjaqt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtidejsmla.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtdzlmvjgj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtnvdgxpcm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtwusodejc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gthjiimbtp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtjpnztsvj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gthigbropw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtxyewsvpy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwtcmdzch.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtjcjrnzey.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtmzpynhoy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtqafwgiwa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzabxhea.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtkiulxebp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtnlwccxdx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyexdsrl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtrparuhvy.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtdiomptkj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtjrxwoxbn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthgcdxkfo.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtfpvqqike.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuoxqmrli.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtgtelfugb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtgjvailom.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxeyzhmyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtpqjvkxiw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtqkpbqadg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtuzolfksy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtxzaktnyd.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtumgkmtag.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtglqivndz.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtenmertna.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtkufjcrcv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxlqstdv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtdwzaztev.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqevaewto.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gttgyutsxd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtswzocetf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtemjbbkeh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtesdiqgby.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gttxpwwckh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtefhmdodl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtbvxwakfp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gttdsapodx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtdqtaoyzi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtuejkerte.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtuhopgcmz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtryyjhxxv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtrtxtfqvh.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gttpabzskx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtjfsamjsh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtwfmcesfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtklumeiba.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtqbaanjlf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtwsivgbyp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtigjxhsqu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtxflnoxwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtyqlzeued.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtwdttedlb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtxkvyflli.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtlyfxdhla.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtozmkpixn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtisawcrer.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtorojbfzy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtssaetdku.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdrdvanug.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpchwicki.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtuttafrzg.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnsoislil.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthijgnved.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwhydjnur.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttqebgubv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtxbwlkfxa.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwjffppws.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcqfrmhxa.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtnegytnwr.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlymcqcfs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtlnhjrrdq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmbzzdmi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtkemvolfq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtzktkmrbt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtbrvjvsuq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtjqyrfphp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtqbjlpksg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtpormugkd.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtsihjsgld.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtjokojdse.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtctpcxscl.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtaaesxrtv.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtpxgbublw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtalnccfmh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtzadeqvnw.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtxyjvcufz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtawyhydmt.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtkeyjkaya.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaivgxdyw.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtaqywnfwf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtgvgmwfwx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehrzoamz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtpaskkamu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gttiumcybv.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwfqvnfjf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtqgnqhcfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gthxlyznae.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtziuggfdl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtybzxerck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtqftkqoze.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtgnbpxaxs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtynwghmpe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgtapgixm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxywcypqy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvbftbog.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtnuqseuqj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxajtgvfi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtypnwczvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtahqwmpnh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gthostitex.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtjlakjszd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtqsafaxhw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtfnorczyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtrqbnnnmo.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtdwailyjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtacefrpsy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtxovnkdnx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtltyzjwto.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gthbbcfvzd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtjtsnmsoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtcihvlimd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gttnerlvvg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtvnnlypch.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtarytxxnm.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gthovmkgoj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjthmopsf.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtpgrqsxlx.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtgtbajmrl.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gthjnzkhur.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtailoxdtv.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtxhnzdgoo.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtimqkgpqd.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtfmjylqcj.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtpcmahrsu.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtldbljdhd.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtndjpzlil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtsgihdwyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtdzeezqqg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtifdmyynj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgexkcmua.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgunbzjw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtgysqnpch.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtcajbumdc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtbgecozhm.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gteiabywsc.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsqvxrwe.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtzynklmvp.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtqneqsgwo.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtbrntfnyc.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtnrttmbcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtryhfoxmh.html


<!-- 参考信息 -->