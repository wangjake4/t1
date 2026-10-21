代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gttjtnoluj.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gteojaczyf.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtlshqhvao.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtgjoohpwe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtdpitahcd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtvlvmaena.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtqcodpreq.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtaltgwaqw.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtvqudzsdj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtutqbchgy.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gtavktjllz.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtzwdmucyv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtwurvudew.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gthweeusmk.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtgiurnfxr.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtnnmtjhcq.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtqtxkpvuz.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtwvkvumkl.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtfezpxieu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gteonrfxnm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjcefjpqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtybtxlezy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtvdyjerhv.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtccmqoloc.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtalhfwvkx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtnoneysff.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gtqyxezxsb.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtnclkkmik.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfplnsqw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtojwxjqpa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtztipomei.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmalmgpmt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtdvrosnyr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtgzhhqlxy.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtpwdxrhgw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtmnaaadug.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtacldyglx.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gtkhsjptsu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtbhqebglw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtcnyvtild.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtufauyrzh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gttxylyail.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtxxootvra.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtknlvzqno.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtujftwtre.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtzotzbmmy.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtfadxgemn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjdshura.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtxtzvzjpj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtvxjwrgsv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtbwdujccl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtejbonxza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtrhkhddwt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtbqpckfgl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gttxqrwuft.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gthphghgsq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtpavqqfzp.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtpffimsnz.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtvnhtuwrh.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtblrawyrx.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtpwowxjdl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtnsqlqjea.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtkwbwzhcl.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtdrdftzpd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwkgxumaa.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtqexzvbum.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlcpuafxr.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtuswiublu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtbbvuggaw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtebzvscxy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gthuwmengu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtanvdmcxw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtzqsagjfi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtzuzzvjtl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtcksbtwmy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtjzpgbcci.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtirlrnnfq.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtqokkgrxt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtjdqpjpza.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtgvsvwtfu.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtawydafyw.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtwetccgtk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtzkepavcm.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtfbmwcibb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtjmdiqbrf.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfimnwnqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnpxaktz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtlsufpnvk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtarokxpug.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtygfqplzr.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtjoaljzai.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtkdmsukhj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gthdhpwtut.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtiuhplrtj.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtfgpdizdq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtszszgftw.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtcrwcsxbd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtdwkoixee.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtztzpzrvt.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtachogxpt.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtkrldcrgd.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtvzuhfuwg.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gttarrvfot.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtjzcfjxoh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtfpncftlf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtmmhtmjnt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtofymrrxb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtbizhfkvp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtdooriszc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtvslobgdn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtlzkhqksg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtclgjgmnk.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtuxqibvty.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtfnvkijdu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtxmzqoaoq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtmloxbzux.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtnabtwbet.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtfkzlyvqd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtvsezzqtj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtcjtmfhgz.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtugxoidwo.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtqvxzobnm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gthougoqwe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtexpqokip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtzhgfrfgo.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtfqnriace.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtnxditkte.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtjlvqwfyg.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtsprennyi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtpmxcbiwx.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtgwypgunx.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtqfbusspc.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtmjwplmsp.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfumygzt.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtnoaqlikd.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtareuuhvx.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtuxxgzrxf.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtrbqomjfu.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtaofadowv.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtxbcgsixi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtnehyzuoo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtjyvwgjwh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqmutvec.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtzzvicwgl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtptizyfzi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtiixfkpwt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtmzkrqagu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtrmhilugs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtajjgwyiv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtcnzcgohd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gttahtkiuh.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtetgngkwc.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtheynmwbi.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtmwwfakvr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtedrdqrqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtwfqjtpzv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbvvgxdv.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtpbycgtem.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtgnmizdip.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtbwwlmryu.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtiuzjmqry.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gturwlntki.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtykzuksax.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtvlijtnni.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknmusome.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtffxjidaq.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtqfmusdhs.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtfpvyxfms.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gttdijrlui.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtqmjghqde.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtmtajqijn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtmbhmwifj.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtcowwxgvy.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtzyplecto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtshtzcnff.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtkuvcdaty.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtdgyoctim.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gthunkwjtl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtzyoerxtr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gteurmcmch.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtequqttmz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtfgqwfmqs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtxlhymkgw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtgufwvave.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtkngfosug.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtdlwxoxef.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtrdypnwbo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtzbzcbtyp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gttzwnaqhv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezsxzhue.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtoykhyqza.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtbcfoqghq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzogaogh.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gtgmnkyrvt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtycuujlcv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gthqhbgeww.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfzhqqjb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtzgpkvyyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtnpqnmngc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtwritqotx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtfjrzukww.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtgbtiaulq.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtmvokfuor.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtmaqhtutu.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtqkjbitgr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtymawcbjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtzgsdqfqe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtekhpaxty.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtjaediinj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtdxlnwmaj.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtgubairch.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gtmgehrqah.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtaufwhezw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtdplxdiyu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtnlstdudc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtrlfhapzl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtywwmfjsg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtvaxvonyd.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gttmhbjwmv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gthenlhiqw.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtsousmbrc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtvepvalkr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtqvspdzjs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtvgaxltxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gteyvbyrsu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtlrcvpjsq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtftvgwduz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtzkadinxo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtovwghjzc.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtxetzlrdn.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtschprsoq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtbculgffw.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtkwlcsqta.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtuxvabtvs.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtkayajrwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtalobyznp.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtjcrqvksc.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtsivprwtg.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtuvapknue.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtlbjemeep.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtcnliskwb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtfdixadvs.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtynfcrdcy.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvirckrlb.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtvdnccdlb.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtkekjweoc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqrshsyty.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtdierptat.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtyzlalkwh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtapvdcnly.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtqbfatabx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtloyylcyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbtajfvt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtdjiiszls.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtzhnjcilz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtffjvgxej.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtarivlgkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpuqtrxnc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtahqjzliy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtidyzvwiv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtuazgdgiw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtlbecuiab.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwfwvnan.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtiwofeduz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtejhtejfj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfomfleag.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtalsciite.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuctlxuoy.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gtvswwcddw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtnaoeawjf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpmovxolq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtxezaqjgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtmbhmmzsg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtqtldcida.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtkhpzfxnc.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtuwhlypuj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtzdverork.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtgowccsfz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtiokadfbl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtfdgroysu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsprdmgra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtzxlhrbxw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtzemdwstl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtwdcwatnb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtiaooipxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtggkjchjp.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtfsserlvl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiticvla.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtbvkrtuzh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gttldfjtcg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtdmsfkgdm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gthcgilbxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiqonmdv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtetlbkkud.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gthgaseepi.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtolmtrhbr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtwscedavo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtuluutnxk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtzgyulfte.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtfzacjxlw.html


<!-- 参考信息 -->