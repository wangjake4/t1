代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2fqsbvceh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gt2mltaafrk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2snoshlea.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2awpdgury.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2ohojkkop.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2cgbhkczp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gt2zahbrpct.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ngoxzrli.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2gbplvaro.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2chmdqlgb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ndoadnwq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2glyzdxtb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2askprzni.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2heowgnmo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2ajwfexzq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2iinwmuhs.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2ztnlkvef.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gt2cxfqsxaq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmqfwdyh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zndlhybt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gt2hrqousvs.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2qdmxseyu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbfytbzw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zltmxpev.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gt2doepzegi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpfsakc.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gt2dpdjsnvr.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gt2toajmypp.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxgcrntk.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2tavocsex.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2jcoiqjes.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2ipgrswtl.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2urkgrifc.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2uqalkuhz.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2obctpofn.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2qpwiqnbi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wztucyse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gt2sewtdonn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsiajquk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2wtcitpsa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2ruzaoojm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gt2uxsuuysg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2utvcwmts.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2dgegznzh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uggubevi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2uciqkuwa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2ahumlnyk.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2dqccnbkz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2tbwbafru.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2cvuipnpr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2upoircci.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2svvcxnvv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2gmdwdhui.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gt2dnsnrbdc.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmswvtws.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2jprrjrtl.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2rrnatxcm.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2nohlxbbz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuvaifoz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2midiodpv.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2yepzuegv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2jhdprllm.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2bgtsswps.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmkxbgmj.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2sptdccod.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2shqbbhjk.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2mnuuzsyf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2iqzobipv.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gt2vlmczdpn.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldnlibkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2xiplnery.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2jzofzxmc.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2ffurwogv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gt2lxpzynra.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2uvgihqim.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2slkwswef.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2hagotysu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gt2hbiuthnv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2fkzazsxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2bxmxwwwi.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2ptymbnls.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2srxibjww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gt2oflkxwjm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2lxboxpix.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ynbvffto.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwjzdmo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2tdiltafx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gt2fhgjoarl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2qkwvypll.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2ptbkmigz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2flewzich.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2twvwkxsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2czkfgfky.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2hzpyiddk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2fyfzvbde.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2opgrqysv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2mkgxewpm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spxwcbft.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2idpxfqkq.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2kmsevqqh.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2tvmtxuta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2nlevtcmi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2uraehgvk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2uzvvveyc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gt2tpcebrvs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2dsduxfrd.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gt2uuiyjdfa.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2qdymxosn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2avllxxmm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2irflzamq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2cusmnnvl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoosxfle.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gt2xldzynie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2ccbzjyff.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2uhsrunhw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2genkylvp.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2nppolgyb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gt2tiodwjsc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2gmafaogq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2hsxxtbiz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2tfegvmrj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2uadcxcga.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsonvjwu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2fyopnsmd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgdgtkas.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gt2vtiqbcld.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gt2fcrihiqo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2tailfoou.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vidzeugv.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2ohapnrfk.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whlfryzg.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2ovyapara.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2rvohtjuc.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2vmdigejz.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2gvthpdoc.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2fpbumluv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2csijlslk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2tnhcqczn.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2gohicjdh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2rokwerkp.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2vzmdwlob.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2nvndkaoj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2awfaqskn.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2tdthyxjb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2hxfshthl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2lcydvjpo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2kkonywnz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2gxsdrkns.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2vexrqqws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gt2oycyfiqq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2xhhqkgel.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apdtjevt.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2yopgsewu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2rjbnejfi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2jsqkllvz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2qsgahqwp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2vocezhpu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2agoojsmo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2pckvqfbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2vhpwujxm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gt2ywyncyxx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2txoyxowo.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2hdrlhedj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ndwqypuo.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2fnihyiik.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2kodcyvtc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2orlpzdvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2srvxtemz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gt2jgrvqcfq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2wkwnjaot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2fbhruikk.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2eibbxwry.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2mgbtxjno.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2rpieihhv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gt2eshkltne.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gt2sbnnwche.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2puwiwwln.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2ymynybyt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2uomcqcti.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2ikdlvyej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2whibbckx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2zusndlij.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gt2vrbqqbzr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2yduqkcgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2rivafqhb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2ievkbluu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2ssdyfbwv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2inlkngum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2pzwulifu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2gklsxbkv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqatjhpd.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gt2ajinfldi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2hwxewinu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2nwdbrvvp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2fifswbvx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2envnnebp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2zmjfonuv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2kkijhwqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2slqyetjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2djrgioap.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2dflrktnf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2fzdxoiem.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2yibbrgjc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bcrjtakr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2vxaxooip.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2vwmftiuc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2rreopcoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yhfnapux.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2gwefdqxn.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gt2nruybhnc.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qjrioblg.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2eezhofbr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2chdalybd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2tcdslofl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbvcaosm.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2hilpumbc.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeilfyua.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2clnocinf.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2rloeqxkb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2yoruagbu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2gbozghhu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2iokqzgod.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2wqulxutm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2gjiyioue.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gt2okxhsfhn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2jowchanr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2cohexiii.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adfqbipl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2bbckglyu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zewcbcpg.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2jkxlarbg.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2jxzxbfgj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2igvwalbk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2ywinxijy.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2zozyrnhv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2zqehyvfv.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2cufigafj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2reglsjsu.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2jfrbihsi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2yxeninpd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2ftdmvfht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xagdvgpn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gt2yvzuever.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2yzqeklly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2kocixwfb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2niyklonp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mhgrwpwm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2yiplbwrp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dniyygmj.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2hmbkzfwf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2zzpicwyy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2bkrzhabj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2ubldhoue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2uczlwnae.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2vzjyalzv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mlwnairc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2kazapryf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2fsatcrua.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2sbglblzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2bsjwjrfa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2futsxozv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2glhixiqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2tqhiaclk.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2ogfqkcgu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2eykamvca.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2xgekkjrw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2rvapdlob.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2xxutajmc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2wqufsoln.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2tnjvytae.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2txlflkzz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efjkxyvn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jltbzqrh.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2mwbwrfun.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2lwhusrnr.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gt2mkziqxps.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcaanvjg.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2arduyiug.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ialansob.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gt2wmlstlmc.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gt2jkzaiwcn.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2yjikdgps.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gt2bbagbind.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2sduymtfy.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mikdvebs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2jiqrveva.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2tcfzqmxg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lpaneoep.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2kyumuetb.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2koksadlz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gt2bgeudaja.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdsxwryp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2sfwmeakf.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2fohsiqfm.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2qtfnfijw.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2wdddxtxl.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2fmxesesp.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2pxrewrso.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gt2plrrkbla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2paemnvkp.html


<!-- 参考信息 -->