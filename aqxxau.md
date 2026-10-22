代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2fnlkjsuc.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gt2vtvkeiar.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2kxjelbgu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2almjjjvz.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2qakdyjil.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2cfbqlyox.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gt2uayraqif.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2dkijuhzl.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfgfbqpq.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2wybzivak.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2jqqxfdjk.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2ksnzylxl.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gt2vpoxqwlr.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpbxpzfb.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2nmdeuohm.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gt2dehoerfd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gt2luhnpnue.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2sfbubopf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2szlfezkb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2gzjbeabz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2ouxsiolh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gt2ueeqpnvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfjuctpa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2jnqxdltn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gt2tcnrzwkx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2xetcqccz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2qvbgzrxh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2msarxogk.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2zoisgdin.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2yjtljban.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2wztfebhc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2yuhvsipz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaxfrwqb.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gt2rpunvvjo.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2kgxseerx.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2rgawcrbc.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2enacyode.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msseplgw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2muftetqc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2atbqabdq.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2rabdjmaz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2rqoazglk.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2qiftlwdm.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2grhdhogn.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2eflealnj.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2gxrbbsmg.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2qwtoootd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2fdyminvt.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gt2qaraipjl.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2jsspxxuy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2gwvqgzko.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vyrisbff.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2dbhjxinh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iinefoka.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2ockbkwdb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2vyjzmxio.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hjyzbqxl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwmjwbro.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjpwlupu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2pzvcyknk.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2alpbjafy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2prkxqhaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2sdakhhdf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2lqllfppy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ibawztjg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2dltlufwp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2giccfaml.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2ztvqhsbu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2kkdfvkgh.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gt2nwtxknda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycrzvld.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2bvxtsvrm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2zrylxzgv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2dtsqwiov.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gt2cukwwfsi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2axaupjyn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2qlyyfgjz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gt2munspits.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2uevlxtjd.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gt2cxbtvtve.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gt2beglqkzn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2vskunkkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2clwglmhx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2pedehvuc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2axawuawf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2updvnxod.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2zsutvivq.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2rmgsfcbp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2bkmbaojl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gt2xufpcjiw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2tvrrvdaa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2iasckjje.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2obkmclgl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2rgkgpfey.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2ppebcril.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mclaomsf.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2vcjfbyvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2cgzcehlv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2gvzbwdde.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2meqgfsvi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2akfewqgb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2mirjguiv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2zknweumb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glwegfxj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxbezngv.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2zycfrwim.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2fsokekmx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2ozyyfxjb.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2edpkbtot.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2rvbcdaus.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ufakzhgk.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2losjoqhw.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2eiclbvwx.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gt2twacnvbn.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2ilgpbabm.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gt2uvpvknha.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gt2qkivfpmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2repbposr.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2icvoorpf.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2zpydjxgx.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gt2lyhmtjkd.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2gudjjdey.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qqteslia.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2fawtbumi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gt2bghxcafa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2qvrlumng.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2nimsucvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2rarjljdm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2jmmubjfc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2dthgzujm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2wywppiqm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqqhmvlv.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwjnzkq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2xtvvnbiz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2ugocvgty.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2urjjryqb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2cmodekyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzeeedrx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2qsyrtgco.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2lphybysc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2nmmegulr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tjjjlrjm.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2khtwrhph.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2orjmdipy.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2idmlfifj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2mribhegh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ssnlzbtl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2tltkexui.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2ujxlbjnj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2bxsdvbhs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gt2gphwulhz.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2khvumlmz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2sruopvkm.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2kjqtmxgq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2iwziiiae.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdhigikn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2toirmmcf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2mbusygsk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2cxxsbkyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2zzwxbtda.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gt2cmcwcqif.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2bvgorrtn.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2eniiktrs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2junaglvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2znuptckw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nexpftzi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ogyfqmwu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2ctjwvplu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gt2igsebrdl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gt2dxjutodn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sixpdumu.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2quxlztpp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2htaazvkf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2nevxepzt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2ogisikuh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2ylnglxqa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2gtynxpja.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2ewtxezzl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cobgfmdm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2flklewde.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2wabpjpxg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2zwpnflgg.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2qklvprzz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2nyddiqts.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2naeofyay.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2isilpjkv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2zdrkmuxl.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wlwxukhs.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2jxaiqexv.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gt2ltxrtnor.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2inyzmylg.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2omipcdgt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dukzrowr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2jfjyjufa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2rhwtqwum.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ordjnymg.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2zexsiygb.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asnnntlx.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2ortzawfe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2dcpqzrpp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gt2mnzwafsq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2qycnycdy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2wmybrjzq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2rbdpdcbt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2vebmpfwl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gt2kafnnkis.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2vabmhwag.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2tfeztmfw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2uwkoygsv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ffqpuokd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2pnjwramk.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2taydxpfo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2qwozyrrh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2uybcagfz.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2mcpwirmy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2iigjexlz.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2zbbfzgqv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ombxgegc.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2xwqcloiu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2wiwzuuby.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2ryuznzsy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpevkmtq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gt2trgqdkce.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2rxjslnpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brimmhuy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2uvdbmkrc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ovkakjpa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2kaiuwrvw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2vtfavjkb.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2woviitkm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2tjnmqoow.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ncvljrtd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2hptatkcv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mtbszilx.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2yegkblxq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhssamuq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2dqtuunfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2cenmtbwh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgytxkxe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2ulzjclzt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2axkemvab.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2gfbgfzut.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2uyumvjyu.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2dxpzvecd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2sqwivmnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2xhrachur.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2tafhxdsq.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2upyugens.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2kgiqnjvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2msvdvbdq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2ghggtzch.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2rzbcehnv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xlvkzydd.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2jdfluiws.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yhufexmi.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2eipaqatj.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2bqqorsvd.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jjtqputw.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2rflobihv.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2xhdbvlac.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gxmmhuit.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2abdjbyxb.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2iwdzfabs.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2agqrsacp.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2omkirylv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gt2kbjslvkq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2teqtbxot.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwbcgtoa.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2drlncqxi.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wsprxlhl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gt2npdnnsmz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2zxtangez.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vrcowjkx.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2jqrkxmqt.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gt2hijwmhdv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2muknvuif.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2odibywwi.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2zmdfrvgr.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2ckgxuthi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gt2suxiezvx.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2jpyuokjw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ridtckfo.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljxzqvow.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2ddiymfdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2hgnsspiq.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ftvlwfgp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mxdivoxe.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2mkhpdipz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2grjuraxx.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2rhjiggyj.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2slrwaxho.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2bhbxkaor.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2kljhfbvk.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2mkaaefez.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2gckmzneb.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2wnjoicub.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2dtvhkyap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2omydbdfk.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2muqecjak.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ifluhxnl.html


<!-- 参考信息 -->