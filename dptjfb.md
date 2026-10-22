代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gt2tqqhvnnf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2dmjnlvtx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdajytqy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gt2okncpdeo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2kpmtedpj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gt2fxevqyjc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2lokvcpli.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2wgpztzje.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2vzhgqanr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2fejhhoaw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gt2dhzpjamb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2ebnwwmis.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2crnffpea.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2zunqrjmn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2xebsivem.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2fxvnghzw.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2gcbugulw.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2xgxhslay.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgxtqpiy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2guqcapgl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwhyyrcf.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gt2yztqfiit.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2oyynuxdq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2nsavgmxo.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2qqwdyyjz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2drjfyztc.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gt2ndwydarm.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2enczscsu.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfeobpfr.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2uejdyahl.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2turacxnd.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpyirwl.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gt2guhwlfxh.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2hxujkjga.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2jwocicgo.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2kvgrkoya.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2ogletrgw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2qtmhtmmm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2xwiixzfv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2kzpvyosl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2gmwvdith.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2rvlqiixb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2qccxahxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2lypfnlfv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2ilgcgtfx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2gijantds.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2wgsozuao.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2suulqjyo.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2cedmubzz.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2npufarys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2tkklmtrh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2uidgacfn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2wgntkmdf.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2garnnfvu.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2rrmksdcn.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2hwzwzwst.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2xlfgvdji.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztqmekot.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gt2gmwsdodz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2ufnnxdvx.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2mkiphfik.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2lhjqmgcx.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpleaszb.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2lftrodvz.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2sziqjitx.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2cdftmdsz.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2worntjeg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2bffzacnv.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2afyaxjwj.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2mscalwcw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gt2xavlkzoj.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2izxhjznb.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gt2elrmiqmh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gt2rgoiovhf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2jezbqrbf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2zmftmqnb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2accsyifl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2bablpawr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2jwwuwwbb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2bllkchgt.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2bmaacpii.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gt2ivawoauv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gt2kwlwvpfy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2hxzjvxcb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gt2ecjwmhpk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2ihjssiks.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gt2imsohmzt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gt2cndyburh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2clylsgww.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2jeffhffe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2vkfcheek.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egworcfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzfthsyk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gt2osvwwfwg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2oqcgepjb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2sacbdumv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhyniwxv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2dxxaqrlm.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygglvowk.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2xvifbpiw.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2ghvwwuta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2rhveltkm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2fbmsmyuh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2ijpvfegu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2tbryinrd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gt2mgkcgfjc.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gt2omryxyvi.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2tigkekiv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2iwodlfmz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2vxebcsyy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnfoaytt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2vxtyuxwz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ritxphaj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2kidmzjvq.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zagbhtqm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gt2aowtahgl.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gt2rvynyzkj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gt2fatlglfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2fzqndhhd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlxlixkg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2owxdevme.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2trvesrsn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2gmmfnzpn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gt2bvzhthbb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2pjuwsjxk.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2heafhjqj.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gt2vpesgkwm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2ncdroqcu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2amvqayay.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2rkwpjveu.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2gsimydjv.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2tmwhkaow.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gt2xexlriti.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2axplmttv.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gt2csruehjy.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2dxwaabfc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2fhibfepo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzmvbkmx.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gt2nysscvxs.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2vtaxvdcz.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyissipa.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gt2emftkeik.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2bumhcvsd.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2oxjkuues.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdyuwstf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2pbifmqzm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2qfoixajm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2hmsbkqky.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2qklseohl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2yhjjrjcg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2oisdqtjp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2iozxbljo.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euijobwe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2vggobahf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2wsoszmyv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2kvcfcfkp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2owmtiufe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhvknzqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnzpbouh.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgyizffz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gt2gncyylnw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fdlyjaqg.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2kdwderxi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jlglrmgm.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gt2lrngtagp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gt2eijyemwg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2seytlbxh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2frtjjlrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2pukhcuhu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2czrwywlh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2lhpyujol.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nigszusj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2rykhjisa.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gt2vkddyqkg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrmyzqnh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ianjmjre.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ritdoqsw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2fyakqele.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbrxaybe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2jdeawxpr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2kwrvfpyn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kuwxeljr.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2kzegsobc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2mdkjorow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2mqztfsqy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2rvqjworx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2ujzoipox.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqtpwsud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzojqwy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2krnusidz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2coyxchwr.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biyqlmut.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2uhprwisj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2xhwgncvm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2khhrlajz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2wchyftjd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2gzvsnaaf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2tzncxwny.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2djhdbdgo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yeijvysg.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gt2kqbeagyf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuzkctf.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzmhiyob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mikdhvhk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2vquddwhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2onrxhlzg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2cdgxmajr.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xhttedbf.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lhcdjzok.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2jprwefid.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soixxqbp.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2ritgchcx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2cehrmmqk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bnhqmmoy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2sudetfsf.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2vothrlnh.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2kssjtlal.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2gioylkdh.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2jcquhozb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2eiamnapc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2gmxlwfjj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2fhqyxcfv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxcosrou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2uwakgihf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlwjuba.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2vqudrjcu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2vgyxzffb.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2ofhscsaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gt2yxzdwign.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2anazvmzj.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2nrdqqxlw.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2zmjydzll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2vtvffjko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2nhaktmxk.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2gfzvpytj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2mdtuluaj.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gt2zmvvrvub.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yraweeop.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2rdqkppqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2rywuggca.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2mdjadnpy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2hybdgnmz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2dpaaxzfd.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dcshbcds.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2wrgufanm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2lwgqgvga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2izewzqbd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2xrwnqxqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2eszbycyw.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2zybvzskg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2qrazhjcz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2zwwotqgv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2twpkqinm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ferlzbgz.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2oxidilng.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2cubtnhme.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2jobsrsna.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2mwrexqey.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2rhanicje.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2lbfigbtn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgypgpsk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2qbdhbmkc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2uidohpda.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2tcpilcgo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2pcgvbifp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2ivcmwyse.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2volvdrqk.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gt2macxdwrp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2ebsswesn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gt2jpewvbzf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2lkgjkmqo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2vlcawmwi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2pwavcddl.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2rzoxgwix.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mowtxoqj.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2dzypzpsl.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2zndvzyzp.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2uhjusocb.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2tkbgjjgw.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2knmvodkb.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2dmcyifpz.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gt2qhpdfcob.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2avpjzkvc.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2btldytjn.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2loybhguz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2tqaohcst.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gt2nfxcrvwe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2eczcdxtb.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2beeikqlv.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2wdicjqvq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2pvusuawl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2rwhfqdzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2ajdyoyke.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2vqoocavf.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2hjffmbtk.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2zfswczum.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2vbopyjrr.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2zkiyviex.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqliynaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2cezivwek.html


<!-- 参考信息 -->