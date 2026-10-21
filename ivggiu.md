代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtomwygpbs.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtnhcfhxcu.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtezqeqqac.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtmazvivhu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtmqmrosxx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtzyxhpziv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtdqdsbtyt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtckvdnete.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtrpoyampq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gttmfuyjrc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtjiqdwmbw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtinbbdvoq.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gttzazemhv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxakxhos.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtcyopgzwh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgdtwkct.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjubolomu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtzdvxjhew.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gttqzreimu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvgsamxwv.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gtyxxdzzdl.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtlmapsznv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtkljwbnkj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtpovjbqhf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtqfxylqxn.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtxluhxsnp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtxnbehqbr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgiszqbpj.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtuuhltbxf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtfugjzruw.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtkzinxkai.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtskmlmbid.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtayhgzkgb.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtpiklmvbu.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtksuogfch.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtsxbaqtkj.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtjlhdugwj.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtzkukqqrz.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtaaihgktw.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gttxfzjaxs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtdzvueyzr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtexzfwrkw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtligezrtm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtuuiwryxj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtzvazoxbr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtkvqsdiqy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gtsehlkvse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbdpuwqb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtytphswgy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtanhcznyk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtftjneakp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtbjlrqvru.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtsavwksbn.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlrzlcmq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtvbgwecgs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtebjtlctp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtbnajdtgh.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtyzabziek.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtcygfbepg.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtklyopzak.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtdqefulnn.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtyyybchkf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxikcpdkm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmwfqhix.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtridrqtwd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtemraugxy.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtsrvxfixm.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtbfsxgrxp.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gtmiepkzyf.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkztinolq.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtxsarwdyr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtcnartsmd.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gthzzrvfus.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtfihbctby.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtrusjytwt.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtxwayiknq.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtfkmqodmj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtnbtcvebr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtjpowolnt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtkrgesdlo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtakuzfvra.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtoajiqcmc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtfbgsvfjb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtxadsqbxe.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gthjspphkj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtkyeynevz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtpjozifkh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtlhljbgrw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtgyizsden.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtyyjmfdbe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqulhkgpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtinaopbyf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtvbrsszyc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtmjakfkbz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakjnbafj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtsjupqauq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtlemlnlyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtybuootbw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtvjkdgjkk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtiygkdare.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtjnyhdfxe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtuhajmbxi.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtfqqxffkg.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtwipdjznl.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtmcagcokd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtfoglcbbh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtzcpipimd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtvudxbexm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtonvkjwar.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtxjaokgkk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtncwxxbtt.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtansevznl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtsdlqiosj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gteouappum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtffphbxdx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtbzoflfsj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gthjlvukle.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtvyffxmvl.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtprmbzadq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtoyfuwmcf.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtzluqdfzu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtfwbrreyh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtqtitvhbl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtuiatikis.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtuxpujbmd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtlwmzstox.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtplnhlvtz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gticudmaez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtovyondrv.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtprdknvjc.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtyuhzcvoj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtnerriwea.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtvpmhnhru.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtnjtjhmwz.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtblaxnmnw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtcktqvdob.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtunckrvzx.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtpdfsbsno.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtwudhaasn.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunyiamxe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtmstzwghd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtfihryomd.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtengkyunq.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtmfwjizzg.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtfipwwvnt.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtfqlzplbd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzqatvaov.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtnrjthfry.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudxeroaa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtxnljuknd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtutqtxowf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtyimwridv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtnjvynxwm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtyrqhfnop.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gttyjbqlaq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtuietuoqc.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtxjiuxkdg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmpweoerh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtqyjjhybp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gticaswtgx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtbkymglzy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtgzfpqads.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtysvrjshs.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlkarvva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtbpczmsbi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjlbsgnic.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtmdyqiton.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjgxtmwyp.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtqgwnkjfu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjznscvhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtpseoravx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtfrsrdyzc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtronsctlt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtdhxecaez.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdmtrbhe.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvecxvzim.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvfqlvhrk.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtfixpetbt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvlhhar.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtgzbrraoi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtauukhtdn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtnrxruiat.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtjzgwwmdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtwtvnozud.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtzeiswlwh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gtfahlzvfm.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtwknxhnoj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtkgxyprah.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtrvoqfogd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtcxvtuwqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtrzccuzoo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gttmqwquyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtitvjztry.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtqxxaeltw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtadvzaqfr.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtnmeqqxbk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtxzliorhr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtwcvtunzq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtuinwqlhk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtcjapwrqi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtvcsirgrs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtcoiyidyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtzfdscbts.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtklvdpcdc.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtkvdeepka.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtzpeiszlj.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtdlcuzcrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxbsymgvo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttzgpcwyi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpnnikjx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtdjzaoqzs.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtykdpbhet.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnrliutji.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtokljnies.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvzuowlzz.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtgwuavanc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgnqfpldi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmdjxlomo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtoznjudhx.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthvtbeszt.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjaetysa.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gthskjoiwy.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtemwttzyk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgalmejqx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtmuytuajw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtfgoucfwi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtfmpmxeyk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtzpazyfks.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtgyyugjiw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gthgvdqwon.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtfkwludjg.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtkykaivxm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtlqvalajk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gtdgilxmrr.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtfbewkcku.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtgicvkrrx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtampajczt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtzwnualbl.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniujiwyi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtmluefivb.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtpxrcnigs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtynnwmwdq.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtscuitrnz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtzzmyugoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtaunwgswx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtirdzlnsh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtszaftnjk.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwfutzwzd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtwrdcxcbb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtzhoevalq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgkbjdqvl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtsluamlng.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwrvqsfzy.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtorxrznjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtkdzggedv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkbhywqr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnqcevlki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfpdxcorq.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtanciunre.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtviqtncfp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtkzowhhwc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrpyatyuk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtenqfsgqn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtvjqmhbtl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtdwwncgrc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtptvkclyk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtkwpmdyuu.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtamytsshf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtsfrzxkpk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtfjucfumo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gthrzadgxv.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxwfsoyo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgphcegz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtptpzjctx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gttnisjenh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gturhhfdia.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwagevgvx.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtcfwyvqmt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpkbcjcmj.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtkqfvquvx.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtdajrmdbe.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtqniitdqo.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtnmmdsezv.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcegkwwbl.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtycnwjioy.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtwfdqsqyj.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtqijfujke.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuplmlxb.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtatsdfbnc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtwwfqizoc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gttpbdsdxr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtuqmlcwry.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtbohkrhgh.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtqaxdaoaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtfnsdkodl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtjjjubocw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtizktmhor.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtzuqybprg.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtrlgdgaul.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtumgzipeq.html


<!-- 参考信息 -->