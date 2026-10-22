代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2wltffpav.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2wkkmhzlu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2gantmhpj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2uedsizsr.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gt2hkyimpzl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2uoyigxwe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2cwsrnfqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2dvuafbbn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2axflitdr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2ahwxwiwx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qkrxxgpa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2arpmxmta.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2dhnyykdn.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gt2gonsnayl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2hcoypmau.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2ectewpsr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2bmfbxudu.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iawgljmv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2riqgllps.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2jikawiis.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2ligaldja.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gt2yzcgyzpf.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gt2hymcxtog.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gt2gvaqiehi.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gt2ebbgrtnm.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2cplnacsm.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2yfppdxxo.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2gothszgz.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2buunfuyj.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2mxzxonay.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2irogcpeo.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2oximisiq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gt2elxzzndk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmtyvtxm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2ugmyjgxe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2fyingikm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ataqtikx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gt2qzuiajbx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gt2wufyaldb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gt2rzyxajxc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gt2ftorvdba.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2pzgnusil.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gt2cjadurrw.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2hsykbitq.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odogiwjd.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eizcjwmq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2ianrwjkg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2udkqushw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gt2vbroonmf.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2cwpyqnrp.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2lsveiior.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2ejsnmbtc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkybpwf.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2eamtmqff.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2jgzyyxdw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2vjjmhiqs.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2zyldhktw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2ppbimlfs.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gt2tgwhuijv.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2wubbhbkl.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gt2lveqrwsc.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2pfbsyadl.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2udjfnbcp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2qmyygpvi.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gt2pddhzeoa.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2bwhvgxox.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2ihjobohm.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2tstklylh.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2torgbjfn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2utsfepnc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2ctomnmkf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2euxrflvt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2sftfjrml.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2ubjgtacy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2wulwyuav.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mbcbxnfy.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfoztjle.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gt2dquphqht.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2wciqlnds.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gt2yqeluoea.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gt2zmzcijkq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2sgbrkqrm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcndhtas.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2baseljfc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2okmbagfm.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2vfociroe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ebtrqgqk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2qipoceqq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2jdmdgowi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2darcqzxi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gt2xjfmigpo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ctkenznp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gt2zvmjwjhp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2kugpecvs.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gt2mvqtunyu.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gt2jjowrmih.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gt2jtxyynvd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2rdmdhpit.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2eyjbqrbk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2byvtworg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2vggjptxw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2rlaswhmu.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gt2gvaaojmv.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2beiwbfcv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2ehnvjhvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gt2mfssfykg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2igroofjy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2ydyhdabs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gt2fpvkcxqe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2tqvjpkyo.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2kaseqkjd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2xnmqpvxo.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2xxmrloeh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jabxuwkz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2hgpiuhwo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2jownhuwp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2senrhuvt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jariihyq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywefqylt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2idjoajke.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwbbjgln.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2xonmdmmo.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2qvllrgyi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2dgnzcdko.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2vtbitvjd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzgtjlpr.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2leqwhnrn.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2tvhlymyq.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2aigsjmqs.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2elmxvxxb.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvtfneif.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2ktisvppe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gt2nbphakkv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vxorwyld.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gt2flrhyqfc.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gt2tyscincn.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2tymktxou.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqndtobs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2sjcsrxuk.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gt2qlnxkpbv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gt2tbbhlggf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2jruaswdt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iekvajjf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2bamxvmiw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2wgucmlpc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2qufembvo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2epbnqtnv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2pkafaujx.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adiikhze.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqvjtcpj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2iqzqonkw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwapsqyn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2sampdqlf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2yiyntueg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2pdaqskql.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2gajbfhtg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2gucotmsz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kzfilluv.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2qurnookg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2omxxmypw.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2dydlkvsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pngcokhx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2mtqulaaj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2fajmnxtg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2agfuzees.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xunxxkjr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gt2ahdhpsik.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfqvxwkt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2vkdyohmz.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gt2ndpoamih.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvegrdfw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2epwygxmy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2otzozlbn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2pbfhndfs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2gtdilijh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2nwcnkdds.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2ulpgxpcb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gt2uatvmbqn.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2twhibick.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ritxedzc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2bmvejvnk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2jhpjuiii.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwkpwlvt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2rqsfvafv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvlshdty.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2kkgkeqif.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2sbgzrdnv.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2ejrkrjyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gt2vklyglcj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2qhqplymx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2fgbdzdqz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2ykmxncuz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2xelnurkc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2wsbtmxdx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2wgkjshhg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2egunzuli.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2wxewhxqh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2pyqzhagf.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qxujinpt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2tbyzvipv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2jtcaxzwa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2godpkiaf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2umzwnhao.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2cjningzx.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ekzessid.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kpdqsztb.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2rukgkekg.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2xwotpmot.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2qmckrcju.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ipklkxyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2omumltbn.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kuxvhffa.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2lbvrdvmx.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2drtadzxj.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2nolglfdl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2gdhqwmsm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2ouqzzqvl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2qonwvpty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2ifbuzaiu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gt2phqrqghv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbldyglq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2euybfazu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2nfybdghe.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2bkfprqru.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccztlmyb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gt2ovomjdcv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2lybpnivh.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2skmrfzdr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2ctmevuwj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2sfuyfevn.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2daofexyp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2qiqyydug.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umezwrec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2lqgjtdqt.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2rpzeyijz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2gvkfutjb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2sqlcojgy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2nibagdqr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2tqppdowk.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wkihusht.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gt2iqpnylfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2emqjxtov.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2regqnqap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2jfiiprry.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ckgghetv.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lqiksdzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gt2xaexoxbd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pbfqsyxt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2hsjxewmp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2omihfhha.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2stbzlofx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2lffayrdh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylhcivmd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2kvtjgxiw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2nzrhijep.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2fxwjoqxm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gt2gxedunsj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2fohmakuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2ahmspngn.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucknrxim.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2bnlanlex.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2rlezdyai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofvczkbi.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2uqrhuvyc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2rxkwbxie.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gt2xjvtzvvv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2nypwgjdt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2wsjtpdyv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xvttylxd.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gt2hybglwzf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2cezcpqkz.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyzqijwh.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2bczjiwvf.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2vmpkjhcm.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2pibwnlxs.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2bugxiikt.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2svhfirex.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gt2betixvbj.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2glqfafrl.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tgfwqfnw.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2qwxttutd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2nixinvlf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2inunhizj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2bdblghtx.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zsxdhzgx.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2plmtuazn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2qzjwvvkh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2uaotuupp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2itirfmpo.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2ehtqijja.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2hiyvnceu.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gt2jymsozlt.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2exezeexs.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2cwbhqfbr.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gt2llhrzsnn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2nmmvzmox.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gt2blemphah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2rupnfqxm.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2kmcylopc.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2upfvkgmh.html


<!-- 参考信息 -->