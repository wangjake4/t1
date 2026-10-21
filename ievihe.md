代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtnoyfscng.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gteygwfoaw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtfuhwfpdv.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtrlabupua.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtauntwhca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gtnfkzbjcr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gtqgkmobsd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtuxbsnzmg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtibmaprbx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtlirpbbxl.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbuupkwa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gtuytbwmnc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtdizfhjaq.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtjfpjmevp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtvmxhmjns.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gttlsoxutw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtkgpeiklg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxsebmoir.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtcstwxevj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtvysjprye.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtlofmmojr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtatejydjd.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtahilvvie.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtigbysxbn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtmajpdhcc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtngzkepkp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtvjpjaqit.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtloqervrn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtpohgrxai.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtancvdnew.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxepougb.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtparkhjkm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtarrifjjq.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtzxigkace.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtavbkzauo.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtfpuywsfb.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtpnxzbgmf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtdeycucyb.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtpuitjeso.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtidjzzxdb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxnuslrlm.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtpuvecgfb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgkgcxjpx.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtavjwxltf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtclwkpkct.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtgbihfozx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtkliwshxb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtqmqkrdii.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtwnhxxtxh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtvirobvzr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtqxrfukfs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtviqrkhot.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtmkhqcdsp.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtrdmwxvdi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtakkubwuk.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtltxqrcto.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtzwiiqrph.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfjkikvro.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtnsnuusvm.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtkcmyfjjv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaksfapey.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtsstyecum.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtzaokqltb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gthiagwgfv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtwrkcfrmp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtgvkttlcw.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtaqhpllzq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtgkoyarlr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtvhagvypy.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtdjlkwhte.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtkwxxpimf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtzhgbeqad.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtxnugjvnk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtsfiajmii.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqcyjozrk.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudgtjdcn.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtympfuxxk.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtmqmaqyuz.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gteuyegdpt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtvoklikvc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtrzpxefds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gthjbnlkbb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtsamnqpsd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtmztxklzh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtxywiqssb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtcjrhkqnt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfchfhbb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtkzlejvdn.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtwhpbkzlq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtimijided.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtrrqkffxx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjdysgfzk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtgwhxqkek.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjlfybmke.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtpnomedqi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtonojzwzj.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtsostznno.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtfgtyswiu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtqoqgskku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtzocfhqpb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtlejjpsfw.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtvbrfskxi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtyiptcyhz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdzobfdml.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqaukvnx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtchttbnqy.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtdnnlwuac.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtczkcqlgr.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtuhhpseap.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtkqvrklmb.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtamvdkqsw.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtgkltwrtx.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtbsandjwr.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtdgilnzmv.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtubvfieta.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtkgolenxy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtdgullgqt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gttotyarpi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtafagcjfl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtzwebhseb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtrrataytq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtorgdfkqj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtuslsntca.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtjthpywyi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gttvvrociz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtgepxhxwz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtpkmcjpfa.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtsicdqxdu.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gthepdcbkm.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtvhbidwde.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtjmezkroz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtfhqsycwq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gteelxmxvw.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtzkukduoj.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtxjyqzrfj.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtnazxghmp.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtrpdqsxnp.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gttprdfmbk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeyqhbbj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtqeumfpnt.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtcsrtsxhm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gticktsboo.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtpjnyoacr.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtolijytxp.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtbdtdoizk.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtxvdzkkwh.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtzczcbfow.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gttifvivpf.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtnwaqaluv.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtqlyyoooe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtxqrgdnfk.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtgwflevyj.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtkrjyrypl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtiwyqlkey.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtudzmvums.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzulkxcww.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtvaligwtj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtylxaxukh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtbbycssgd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbglmjzez.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtnekoxanu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtmeyhdsrz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtevglbzye.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtjnrofadj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtzqkwshoc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenuymzgp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtjkizicbz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtikgkyffs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtofobtiut.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtjujzrqvk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gthbrttrlf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmvzmwsn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtjecqhmoy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtieninplp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gthzyossbo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gttzyncoex.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gthjzommag.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtifriejle.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtxszruuvs.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtpfdxeolu.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtlcfmwjep.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtinynfdtw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkxzlzlm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtikurkwkh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtutgkdfio.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtiozcffar.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtfjoakmad.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtkdvmeult.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtcesfomsw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtgobyaofr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbxomcmdp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gteqcupljb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtnqpmdhnr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtqqoelgkq.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtbdmxlcvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtxnefmqih.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfggvndbo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtuspuxqnp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtfsccbgwt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttidiqjit.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtozmkbsoa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtthzocrrb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxuvoupv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gthkvfvfbt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxzofyffz.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtubynubsy.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtnwiunpnd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtsxlrggjl.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtbfioqmrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtbbfugxpg.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtrbfebvjx.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtqykrchzl.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtdmemfrpw.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtdjyunmdj.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtubxhunbl.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gthawoovag.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gtmtaazomf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtzfneamlb.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtevzjnowv.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtyrelstzt.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtrscenbrv.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtedxjvhyr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtubebkomc.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtlwknjgby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtiynofgxp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtcgaqeabg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gttknpkxjs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtieabhnob.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gttjosmhzi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gttmxfroon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtgeaqifbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtncdijgra.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtefdurbez.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmpprrcez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtexpuijvh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gthgxsgoqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtdjhvgrav.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtkkkkpnsb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtgeeiacdo.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtyrcilzcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtpgirkoog.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfuabyntl.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtbgtimhvt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaivtkkbs.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdgwpygfm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtskopgzoc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtfjjwunmg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtykmzowig.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtyuwyputx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqoucezi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtujkhtayr.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfuvhovb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtelfskcai.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtfqkfxkzb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtdzndwwmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gttsaqpenu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtilfbphig.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtxhbpbskp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gthtrrvtuj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtkxjbcckw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtbixzdujq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxgksoxd.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtrwghjwks.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtedhdnbnl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtlazmgccr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtyvgegllf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtcztyymqm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtahuvzydh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtgryddgts.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtxbfcrkxk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtwsdoifkh.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtynoeaehq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpusvfbqj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtpcsiwpnq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtxcogjqoo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtegcthiwa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtqhpuixgx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtyggztysf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtzhvhvkty.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtvnvpvada.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtydcthmgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtoqelqqzp.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfvhakypa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtlbcwmtsv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmgopafit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gttsbkscfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtwngibohg.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtouyaishh.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtyunwtzwl.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtvfyukval.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtltfkugbb.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkgtuiukk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnwoymfea.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdxyecngl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtgrfjobul.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjbgfgtlj.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtquhnkjuz.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmikhbwgh.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoxkowno.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtnunrrqui.html


<!-- 参考信息 -->