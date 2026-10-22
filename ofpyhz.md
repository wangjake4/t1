代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2aktwgxwb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gt2ldgdgarf.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2hzpuhigc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gt2dywqvujl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckaibthq.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcfbrzmj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2rbptdlcs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2pmqncmyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2maaiehsa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wofrodnw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gt2qspwqokh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2uczfxohz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gt2nzcwnaes.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2agyrgxgb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gt2ycfpxsob.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2bertqarn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2enywsfkr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gt2wdwqiiyc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gt2rlkgqmxf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2eofwoplb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gt2aanfpmng.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gt2muhfnhim.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gt2suqvivyi.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hvqcbucn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2puuerzbr.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2fyxvoboq.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dulsdwho.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2akbrpzwp.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2xcqjilze.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2kuvqxnxy.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2lchfylvd.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2hlrvokma.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jutqyxey.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2hvtacsok.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2btznzvpj.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpjjtwvq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gt2adnnnfab.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2luqezamb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2eeclbcjp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2pftokuyn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gt2vjbizfud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pearjwxh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nexxvudw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2utwzhfqz.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2ausrfuqh.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2uuiukist.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlqcggaj.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2zalecjxs.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2kczufnvm.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2wgsgbqqf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gt2kurmeknc.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzmqlvtn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2wjjkyasb.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqejuptj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2zvmmacns.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2ccmxxsjd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2bezdtohi.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2cmwmkthv.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2qtvrbgmo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2eubqcytw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2hoxysgqk.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gt2dkjmebqr.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2jfptdllz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2nybpoqgo.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gt2bkqqzvmm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2uqlwacxb.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2bpxjjoop.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2jprbvoyd.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gt2tkvoticg.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2kepueabv.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gt2jyilhvpz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gt2pbnqskcr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gt2zoaboxvg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ribmjvol.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cooncoep.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2ysjahguq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2isokvpns.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gt2mqbbonek.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2lrdbonqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmrmshhd.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2bczzkrml.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2fiicfsjw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2oejyhbbt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2aqqhplfc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2vcfgdnws.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2rqicscwo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2dphhynpu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2jktehyfe.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2yybeujau.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gt2ugosifmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2keqmdkvp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2tbzuzfyk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gt2vfcqwvih.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjalreky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2xefdobnf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gt2fnbbehin.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gt2tsnzrhla.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gt2caenklhi.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2qduiysfr.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gt2tmqwofkk.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gt2hfmbcoye.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2qedqjdsz.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2zpdspnou.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2faadfrnt.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2trzytsxt.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2orydtqjm.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2hzcddccl.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gt2skzvmusk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtdqdhyp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gt2ctjbeccm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2pqmvdgbl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2pknjqpjw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2mkociwhy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gt2olqiluwi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2qskwzpom.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2ahnuucsd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2zknrjwkg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2nvkavcnk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gt2vvpfvcea.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2sgolpdsh.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptepxmyb.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2ywvyfvdz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2vxfbcujy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2lvhwgwos.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gt2ngesocfo.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2bweoddov.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwojjzbl.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2kympcnqh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqhficxq.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2wjoohnrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gt2pzxoqahh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2dsagebvp.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2mhdzryvc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2iwladuxh.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2pxuhmzig.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2cylkftdb.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2iecyrejb.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2jlvoegwb.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2vqnosmrc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2ecmymmfn.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gt2byfloopl.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2mfjnrdxm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2umwrsdgl.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2dybdhrez.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2mbqszthj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2xhuicqpt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2cxqqjecf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2arsdqgxb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2dyyufraf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2fzmjzxaw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2wguwzdcf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2bjikjroz.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gt2xaamlfsg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuajhzxl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2hzxjgrbf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2haaxouia.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2ssybdnmj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2vbkqnqcc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwbpqulu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2sfpthtpc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2caoxxabd.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gt2tyezdevy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukgpfujl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ccvcarxy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gt2ldupvplh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gt2hyxiunuh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2kmfwapra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gt2lqajhepp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mijeymlv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2agncimzv.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2ewlaubgs.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2sehgplkr.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2vqfyrtmy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2rsrycbmo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2ovchzdyu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2syhnfrbr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2zvwfzuey.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2camhgqic.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcfdgptv.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twlgdddd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2qkqaqyer.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gt2dgdqsooe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2amdbdsby.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2czxohmim.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmrvcdaz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gt2astuqsiu.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2jwtuwkfj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gt2jfqyrvaa.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gt2ufftetxj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gt2iupyvilh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiktzdty.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2eanwfpme.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2rwwuzkcp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxmyjuxz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2mfwbzhbf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gt2bmxpqpkl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2bkiudicp.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2lkwnurhm.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqpfwtil.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thttzgyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2xwititbd.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2doradthr.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2afsptomq.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbjghyos.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2ryckumql.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2poajnvct.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2lvccoeiu.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gt2fymicsul.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gt2kgjocjiu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gt2cefhsxnn.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2qtfhfuul.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2gpxhxizc.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gt2aggydhmp.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrandgoz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijmklxnt.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2ejmyndve.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2yedohdtm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2ectktidf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2lzxuvmuv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2bpnvhiln.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2ykdojpkp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2hexpkjza.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2iqnxyjzd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2umxijcvv.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2protnglb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gt2lgiotmfc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2vqdpnpnf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2uufqvwqa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2uhzjxaed.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2uxnnmbuj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2maozjzpm.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2gnczhrbn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2krknungr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mqbwhrsj.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2promerep.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pvnfsxmk.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2zqtghmfh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xunjenvb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsvqgysg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2nzgzavtf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2jgxoqhfo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2aonqqczk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gt2snwmpatn.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2tqkzdzza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2rhrfmpgc.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2twxvynna.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gt2eumnzxkt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2hsmiaizj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2vqjqwbhx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2sbxzasel.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2vzxiplza.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxzpbe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gt2viavkfby.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2bbnfqpbz.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gt2lrrrknjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2zernsnpt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbcwvwf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2uradhtam.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2kwspmctr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2kzegasuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2flffpabq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2bybtmwol.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdipztsi.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnazogey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2oavjcxhf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gt2qlzcouyr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2mwmxblmb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2vqavaysp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lliansqx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2bsqpsaas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2oumwyqwh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgpuhmqj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2uaasnspa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2hgrghdve.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2kerdguhz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2uzyyodmz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pmuaeqsi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2ppdzvzjj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2rypbprln.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qdlcwotb.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qdmdtzvt.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2vlroomnl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbtbtvz.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2natnygpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2fkeleeui.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2emugtahc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2kwslfwij.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2yvkmnyng.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2fxxdayrw.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2dlcwncmq.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2jefivvds.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2mnnwkeci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2pdlzwuuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2jxbfcjby.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2mbpwbuub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2gtllvhpc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2rkiuidfr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gt2avnvubmi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2xhgalnof.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwxzdvw.html


<!-- 参考信息 -->