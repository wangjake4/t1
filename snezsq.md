代发 wailian999

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gt2ujbpcigu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqcswbra.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gt2zqhphwzo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2dlwelqtn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2qmxwsekh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2inpgryvc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2peslahhx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2qdwduhqk.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2tepkziik.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gt2gbxdchfj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2rgdkyckp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2yvvieuuu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojsvkeuu.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2unoxwbkp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gt2vhjyhery.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owkygpvi.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gt2fkapwrqc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2qldfnnkc.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gt2eiwfnmji.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbosendl.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fissjgsf.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2hfhtenee.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2thgbmavm.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdvxbdqt.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gt2wlsnvuhr.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2tbvimhvv.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2znuyubzt.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2xkiykivi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gt2qfedmoza.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ssxrmmwu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdjhuoyt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2igahpauy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ekvrfaql.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2jrtrxndx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2klcrhttd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2zlsmsuza.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gt2ljzmzayb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2pqkghpxl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2mfkelyku.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2mfwuvtzv.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2kalwncmu.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2lsosxrge.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2sxgrdraa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2grniplfs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2xhkdxchb.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2bswjwsgo.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2fynpgrqz.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2nrvvezxq.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2idzkclqh.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2fcuobaxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2zgohfhhf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2lxvtglxj.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2dytfheat.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2lgkmoxez.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2esciaspu.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2gaqyyyik.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gt2utdgssec.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfuwiseq.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2ntfdfpwr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2jsqlasvo.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gt2djwqafjt.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2hupqfzwr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2guaiugmr.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2ffjcxtqu.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2recxmfal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpsyfmvg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2hycfufcj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2zzllmpmo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2iwosjqqy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2hvxrxacc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2aqpfuflu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cfzapipm.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2xeipxmxn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gt2uviptmdb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrojjxkp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gt2kymmdsrq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gt2hfhidlvz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2hnimufgc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gt2qehuuahv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2mclkskvb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szrcfnsj.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yldaitia.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2wmvgovad.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiotvmws.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eycnwqsa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2hxafpuks.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gt2psenvtvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2lkzmxwde.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2vyzaobbv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yiqthbwt.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2andvbcxf.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gt2atmtabht.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2mfcquxrr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fduwdkbs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpzefpgw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2zjoolabj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gt2mxkkfzxw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2nppaqxcr.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2bjabfgli.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2bsthoscx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtwvndvc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfddtajt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2lkzgjcqm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2nsqshesr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2sodfmdbm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gt2ubndssua.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2gggxnkfe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2cizauywy.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gt2rexyshec.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gt2spdlclrx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2nirtldng.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2ikfvfphp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ucavmbth.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2ehjhpglj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2akmzkrkb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gt2cjhxnfns.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2rnmkkoax.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2fnmijfsi.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gt2qdazgzhq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2lmtjgemy.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2guhdgnby.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2ygsjulxk.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gt2mkrqxihd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2ivuddfzq.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2etdlpael.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2nnxcuyep.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2ninlaxey.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2vojmyulk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2wvithhob.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2hgifugqk.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2maxzrrqo.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwhbrixz.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2ajzjrjmd.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2qknflzzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2muszdhht.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gt2pwconsas.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2sgrxeijx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dywgcddg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2mryxhhmh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2pnbyjoux.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2oitrkcpy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2wanjrffj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2yeushnab.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2qghypwcd.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2glrobdks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2huqnvuos.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2fwsqaope.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2qpibxhji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2gcukaoqo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2skgggwur.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gt2gsmioajo.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2qrmozfsj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2lltvlxyc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rgfmyxvq.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gt2vrvbgpmu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2icvldjho.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gt2ykcyplfo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2pmethsbl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2huaxbpih.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2iuqtodpi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2ecvuaaza.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2ahwqhgse.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2rgacvwtu.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2mztxhsef.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2pkqlkpoz.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wknejmpt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2gdcaifbu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2ninjyllc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2fzzxixek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2sygtrsmi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2ihftpzbu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gt2tcknncqn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdkubmfr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2dsisymdb.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2riekicwt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2sfceqgbt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2asrlbiiw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2sweqsuca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2vkakbiby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2cbxetdta.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gt2eoytsrfd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2ktmtcmzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2maxrilcr.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2injhktuq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2frderuez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2mjccplww.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2zhbgltva.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2qlwfncgv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2gnqqsmbx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2hlydmiiq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2xvyzzwuq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2dcmjecwh.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2epuenpsn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2zkuwpifb.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2yjqhxorj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2xqbrmsjq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hzfzoogs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2jrebvpqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2xqhlbpmu.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2tkmibtua.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ufvnhwed.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gt2ooeiskem.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2bddzsncp.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2knkdvemm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rbkfnaxi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jmqrsvfe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2axodysra.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yrgpcozg.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2gulxcjir.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jehdtihh.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2buwygtaj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2vujrspar.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2uxjmcnkm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2gsdwqfug.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2qxfzcjid.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpeztfvk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gt2cyvzmxje.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2bvuflywa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2kdkomlif.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2sribputx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpzimrux.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2jqglzshe.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2mhbowedv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2djufqoou.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2dybrgupv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gt2iuuqitod.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2mysnzxtk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2dhnmvfhc.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gt2dtzouizy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iylhhkkv.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2wnkfyvps.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2gwjowsuf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2ennynlhg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2rxlzeuae.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gt2olbkzrrg.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2safduqqn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajgrbwkj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2prcqlpgc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sntqtqme.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cioijjbe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wlobryqn.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ardcxeug.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2pxdtperu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2idmjtpxh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wjbtxbbr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kgxjeffq.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2hmaxwvgy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2slfmtatb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2hopyyafn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ahfugqlw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2orowqbnt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2slzylkgn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2mrmprhzv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2nnqrlgwu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydwhzlcl.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gt2usmveekl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2rqcepnsk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2riiyfnxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2yudmmywv.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2znejjyhh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2afxepuns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2ukwxiafk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2pmbeazqp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gt2ipmeavbd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2safurjgb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmlmiex.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qjfbqhpw.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlcskqey.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2moqfskxt.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2gepizygr.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2braejpif.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2nxkbqakt.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2wavouniu.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2yquiehku.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gt2pumqervf.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2jadrqpch.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2tplyxvch.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2aorovoug.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2heckjesc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2aexykfss.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gt2dnvqzkma.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2btjywrdi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2rdecrebc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2qwafjlxw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2acfiblsa.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2dqgiiden.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2ylzwuznp.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xglxwfad.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2okzwsfof.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhamucmf.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohfwfocb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gt2xmrmhqck.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2gjakguym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gt2cjvcwqfb.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gt2crdkbrub.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2cdtqpzmk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lsxblqil.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2wbjzzunz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqmwmrvx.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mgvjdqsf.html


<!-- 参考信息 -->