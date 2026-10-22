代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2llgyeqdb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdxruegr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2wmplvckf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2pqamrdsv.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gt2fckanksf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bizkwalh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gt2fxhjmuxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2wmpnevpu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2otblzkov.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eiztjpsp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2lsnvpyze.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2nqunqlfy.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2ympcozaa.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2bimcocjg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2buchfohm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjqmhoel.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2hpdbgfte.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gt2luxgycly.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2muyzszgh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2azlvzbcq.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gt2rykghsxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivgdjzom.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gt2bgmtwuzq.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gt2mtxhdjro.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fummiafu.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2cppgwjgt.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2wbovwprs.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2kdriyhmj.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2trojzoid.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2xocfnoic.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2jiutrdwm.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2nirxrlda.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gt2yhvpbouf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2cmtchwuf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2mgoqlzbf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpyrycrn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eexqtnkc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gt2jhxqmfwi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2npnjfdcb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2gvchtwjz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2bzlrrlug.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2qwfhntvd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gt2xclkekat.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2mqdgvvkl.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2edxqiohf.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2qvyalfnn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2ztjhjoqg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2fgdrpnbt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gt2zwzqrsqg.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpojtqgh.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2mpwapmyh.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2bthfhotj.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2xfjjdfnu.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2gncvrybe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mbnrfmgo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2arlxvrlc.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2bxuelpwq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2guxaqcif.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2rbeejwyv.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2jauhpjdi.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2hhbzupei.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2ndnioirb.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbffttdw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gt2ghzimhiz.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2nfvyovoc.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2jgkgcllr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwbwdqrl.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2gxuwrhbx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2kemkajbx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2iifqksku.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibdnrzto.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2nqqotaep.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2usgahzfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2ouyfkwrd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2llxzzyoh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwjysitb.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2tepnojmh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2vhuvhbdr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gt2gfvlgegj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trlhneel.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2fcsnekjc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2ekjbntla.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2niuzpvkg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2fvfsuiuf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erbwltrn.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2ddefgxcr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsevdkrp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2twlmtwzj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2yndizwtr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2tnwevalr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gt2ncaczjbt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2rodevgmx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2wvnuosbn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jsdpuxzv.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2whpdqdtj.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gt2gqoxytgn.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2qucogvqu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2baadnnyw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2oerffqoy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2kszjhreo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2hvczzseb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tirdxjhx.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2eggeujpa.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2zqzceqie.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2fbiasmat.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2gnmohpme.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ufbzhaso.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2lvggahyg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lysuhcpi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2uabfutbi.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvlxiguu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2edunckym.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urxfzsdg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2zpvvsfdk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2petdpbdm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2dukapula.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2syijcbpx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2jwdfqzrn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2qolyaiih.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gt2yfunvazi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gt2xzprbiem.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2afgopqwx.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2avoevwrd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2fnytzhmr.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2llwtukai.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2oiywutlf.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gt2wlpfkwul.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2zgcrxjol.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2nmijtwrc.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gt2uykbwkkz.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2lddloahx.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2qchmodmt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhywjrue.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2itihcwhw.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2klwsgopf.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hddukigu.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dholsemx.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2zqlotadw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2fcydgvsj.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gt2dfsjtixa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycpcdlxh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2gkrunodd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2cpazkdhh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2ffunqdyd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epitjjvw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gt2soqjvjqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2aahjrwwb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2xezcebzn.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2fuppqmdw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gt2wgyxicey.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2ebkxdkqc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2pyueghdy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2jrbusjou.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2cdqxlubp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gt2sbqroctu.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2veqhrhnz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzvkssva.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hlqzfclj.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gt2qwikxbqr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2itaawrjz.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beyjilpk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2sztqqofd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2tfvvietu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gt2zxgoyvok.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2jdsmxdgd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2joggfulx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2uxqvvopd.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hcqnzzoe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2ebqykqpw.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2njixmvlb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2aqwkopvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2dwwnujif.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2radimbts.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2svjozfzr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2lnyntywl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2djbumasn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gt2hmsngimm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2rtsffzpn.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2wtcwwpkq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2rzgwlpfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2qdausgcn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2rcysrxhm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxxuunnz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2klevdxsf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zltcmzqq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2ciyxlzji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2xnjofqry.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2stnmlrqe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqhepzoj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2wxzapfef.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2vuqyzbkh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbxsver.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2ielmcdad.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ocvtbwoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gt2ddvzidnu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gt2csidryve.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2mfkqalow.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2algutuag.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2vxbkivsm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfyfdxiu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wdyfgbmd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2bfxmlney.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2kyiftijq.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2oqwurtph.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqtnnual.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2ipfxtqcr.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2txqzykoi.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2gfzbjrpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xzyyyecu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2phqvszax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2ygfppwbl.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2mcpykykx.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2mzynkkxx.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2bgwjgswp.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2lsiymndy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2vwvamygq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2vdcabqrw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2zhqanpha.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2zagsgjlf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2jeqttktv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gt2yivhpchn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2kowmckfc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2reusmcyp.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkijaheh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2ssyehmun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yhceynmm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xegcfgfb.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2kmnsdjis.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2avbpxibu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2atwinfrp.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2luiokppa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeoopspx.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2gijjblyg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2pphvczay.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbriviig.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrfybwyd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2rmhlvkvs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2wdpowvwn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gt2qkoinxip.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ypgfqpwn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2bcazzmtr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2jiubodpz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uzozliud.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2yhrcdytx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhpralkz.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2nfvzzpkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljkyhnkp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2flhqitdi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2kugjxttm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2dgowhalp.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gt2ysnkzmmv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2oscelgol.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrkzkczc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2rajkvana.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2gjtwgjpz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2uqmlyrlk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2cdayqifv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmebuzse.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gt2iqoelwqd.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2ablfrgzx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2eahshgwo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gt2dkuuhmea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2elewhnqc.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2jsavpbed.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2ypuqnqyc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2vbhlzroe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2siwkgzie.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2vtvvjpxy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ltqouysa.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2vfgclgig.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xkgphxji.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2ezgzfmbi.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2lgftmzsl.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tykxltfm.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2nndzczva.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xknhmgkh.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2jadjnpvx.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2crvibxau.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrctzowl.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2uxmekwmw.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2rjvycdfn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2dthmnokw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gt2qexvopgy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2mohaqosu.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2lvbqblvk.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mokcmwvo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2boikwhec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2davckjew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2tqchnpra.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2wiwhdmkn.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2zujmgxis.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2tzphvzvl.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2kxkahedr.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjubezvl.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gt2hfzzmltn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2axypguxs.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwtmzmhi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gt2dsodnjpt.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbwvcega.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2jcrsdxcj.html


<!-- 参考信息 -->