代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2pcggzsee.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzqbdqdd.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsjmjtbk.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2wwdxgvhb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2qmxuwyqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2ifyjhdjo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2pefsiejr.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2uzmhlobh.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2krvocfzh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2nsdioylh.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2ohkusein.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gt2qutdlcka.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2khcegovj.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2lobhmndg.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwmnpmcg.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2bzsrticd.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2qbanbqpo.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqwguusc.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gt2irtzgqgv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gt2rnqefjsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2rngykhhq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2abyjvlgi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gt2fzuvonfp.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2fksagzjd.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2xjgidxbq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2jhfxufrc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gt2otvtsbop.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2edugcxdg.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2kepbyohp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2asjhyxjt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gt2vlmstwqi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2vlomyhdr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2iqmnkvim.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gt2ngickqav.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2qavwzmhj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2lqmhrnql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2ejocnogo.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2vpyxmqpx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gt2kzobucxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gt2axehoenq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2ifmoadkn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2dkuxqtyy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2tljqcwzs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2eehtozpj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gt2jlfudewc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gt2qmjldlgb.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2optsgefm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2bzbkmhug.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gt2pbhlrpmc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gt2fclfpxcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2zeutlmsn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2wugijsoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2dwyjwhod.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2hhzjdsdl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2ughcsphc.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2hbnpagzq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gt2logafpvi.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ukqdnfrt.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2xpnblbmz.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2vrujixly.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2tmicbwgm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2ndjhcqqt.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2poqtjxss.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2rbufzosv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mtcnribk.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2jinyszrk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dzpespez.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2xhbhitov.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2qvhgdubp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2jhozkudt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2uqchqsir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2wegmejii.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2qwkiohyi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2yqmrozwi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2vlzaxtox.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2amhuwmfe.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2dtxwqhbx.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2trgkmpwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhnsgssf.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2iljtguib.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2wxhixhqx.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2aqxpeney.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gt2pphgloih.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2sxewhmqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gt2jxwyydhs.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2uekphbzn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ikqfpgzv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2koesplco.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2ecjnmgep.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2zjruynxd.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2mzgqqatu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2imzxkjqp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2gserhkkh.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gt2ciqavpmj.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2cqyviqzj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2zsrosbpg.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szupzuoq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gt2uxsfbyjd.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2ndqfddys.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2sixokgzh.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gt2oxprerdr.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2ofkbhalf.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2wfzyjihb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2vlzunyvu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vssxszdk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2ltldismm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2sgrgdewg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2hyixdhpo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2vkjfkdtw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gt2iklmqjqi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gt2dhqzcmlf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2burxdvzg.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2bbrohyhh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdyiaqdz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2vcsgwemg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2edmparwc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2zdscnmxg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2bywioogg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2trlkrrpf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2pzviggei.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2yjpvxjif.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2uiruaqnb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awtvgutq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddphrtdy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gt2cmunaurz.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2jioxyfso.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gt2ssqqfnkk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gt2wcrkkqxa.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2mdyuhcsc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gt2bjzuimik.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sklnsfeg.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2whnhbvix.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gt2dzmclhip.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2qqgletrz.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2iklwtyhy.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2qsxanhxd.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2pqdezbok.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2ezvglceo.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbiotskz.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gt2ffkczrko.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2banlikio.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhcsthqp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2fcslsvoi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfmxvvr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2mnamsllg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2qqktzrqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2koqpekpi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2fmwhlcxy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gt2xfysjyvk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2tgfszysu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2coqkfaqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2hgucjxzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2ffdzynpi.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2wyfpfrkr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2xveljmak.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2ynqohkwa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2hfrcqdzq.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2wegajqgj.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2qzxpxopj.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2nplzdtrh.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2qbvgulyp.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2kgsdutkz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2mgzsikav.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2jsvfklgf.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2cqfryuqd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2wtkotpaq.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2fjgabrck.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2mrkobqgz.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2ymcvdeba.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2ihywwyjj.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2erpdnpaf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2yzdwhsox.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gt2gazxgunn.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2bqrxjwyf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gt2kpbgykuw.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2xsifyviu.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwinystg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuolwzmy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2kpqkqeud.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2wrfaxxrx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2ixjdwsyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfibgibz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2lepoxlnn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddsrbnhj.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2pixulkrd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gt2lrascjie.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xarfpfis.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2puxgsfnj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gt2tudfbbhx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2chvepblp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gt2zukxsbif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2xatxxisn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2ockblqqg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2oaxexllo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2sbbuibnp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2vrvfwhvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gt2dzpdjyiv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opbgmkhu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gt2peiitppo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drdikmvg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gt2xfmfxpnl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2alnxrydb.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2xyppehaj.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2xyschcen.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gt2wlclvywn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2rdchtqma.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2czqvdxgw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2brmomnna.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gt2wdjrlaoy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvncwvka.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gt2zkcoslmh.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2wacplnkw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2nfsscyhb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2zvnjdazg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2qyfvybfn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsuewlwf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2yfjyxlok.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gt2nypvndtk.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2yzsueaov.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gt2cfhpnofi.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2zwejlfji.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2jygqltvs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gt2itdxikos.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2ywepseag.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2hpahxaok.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2hfaujjei.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2rzgmgjub.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gt2pzmkpimf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gt2cgagldpf.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gt2ntksspsx.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2lmewtnaz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksgwgkmr.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2pjdivhla.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2nkvokgjr.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2uyajvdqf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2bnlmcyic.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2iczatvmp.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2nhnkshbf.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlirwcfx.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gt2wkpcmiqd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2ekryaeeo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gt2rjzipeuo.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2bppwnysg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vjmgrlit.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzsnbcfk.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2drurvrnu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2tbaualbf.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2hsvbllsw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2rdzdmfhn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2wyltfixy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwkxdalq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqnmlsmr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaikkirl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2fvwtqgdx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2mdtfoyvm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbwzqjb.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2uzziaxvk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gt2jkbzygkg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2bwzkfxxv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2arblbizy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2vvlvcumi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2jfffguao.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gt2wyrozdih.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2dsixplfg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2qustjmht.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2unxafabw.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2ivjrsgrh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qhbrhobp.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2bjazycdz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gt2vdqqyont.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2clrwpawu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gt2kxoscvky.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2ekxyqocx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2lwcrcclf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gt2mrexrpol.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2kvmjiqsf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2sqavvofx.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwokexvy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2csmdhthv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gt2mxqwuilo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vdxdttrh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uawlrusg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2ywngkwbd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gt2adrmvgyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2nbqtadpo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gt2xprxrggx.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xddralfi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2godwgcjn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2lldsgvnh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2senqfjig.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2xlsixhke.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2wogxdbon.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2romqcyin.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gt2fmzanjcd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2znscplsr.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2bgzzpxro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2njimgvel.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2uxdxfzse.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2tozwawsf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2ffsfhjif.html


<!-- 参考信息 -->