代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtvfwkrfcl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaasbwlq.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtjbbvwvve.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtrfzhxhdr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtkqphcsfo.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtflzcnaxl.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gteecqkhal.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gthhpqjeyo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhcsgqcs.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtrgpvdiwq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gthfktmhsb.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtysiqpsuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gthqyaufhv.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtwfbuzvtn.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtmqhnobqh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjixljxmi.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtbntoszxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtoazbxhxu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtwyefxazo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtgvrmabxn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtsdrypnkh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtkrrzpitm.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtxhlzxzln.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtclmnwngx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtdhtronaz.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gtnkekwsij.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gttcmvoteg.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbasbosrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gteficzrxu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawwromou.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtgavtyhsd.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtvdarqrxp.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtvhqiikcc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gthfnwdiih.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtnbtkovtx.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtkacazdox.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtehvapcre.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtwqusebxf.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtbyndweas.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtfpglhvmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtmqumckqa.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gttbwcymsh.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtjtyhupfh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtqhbssuab.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtczhrqebk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtyhyhpvpr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxzffxkr.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtryndhmhc.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtqtgsbars.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtmkwadwrg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtpmzbypuf.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtxtzdevwr.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtsgbomkpw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtxipqmzgi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtoymnzgsj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzhukhry.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmylmudzb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtczcqvhsa.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtmgwaixtn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gttcysacul.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtssngykti.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtgbmukzco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtgyeyiwwf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtlvahntmo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gthzsabpts.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtthsomqre.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtrdghutpz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtljswlplf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtnpikwphh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gttwqumyaf.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtxknwilff.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtxzqofukf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtyotyccdm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzuxmepz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtbhomfqio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttjlwriia.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtwymnxb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtsuvbfhdz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtkvwjyjyo.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtoyihyzsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtctowaowl.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtxdebjuzi.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtuhxwshra.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtltoketjy.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtquqprurz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtiijehjtr.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtkjrtirxi.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtgrhmaxkn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlonsayxh.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtkcbiofxs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttizrhibs.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtedonjezi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtqritewqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtafmovlzh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtwvjwotyy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtbjpptgso.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtoupjwpfs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtvxnakdsc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtssettwwr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtamsrxhvu.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtzqjizpjx.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtcgyrxxtz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtvvdhdtuy.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtffsybzkr.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtencrdpmo.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzbfbysd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gttndrplfo.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gthumsxvos.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtrxrzulwp.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtpaaqxxie.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtfsvixuho.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtklirebwb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegosmach.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfxihpls.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtihkwgdzp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gthvvyubxj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtqcyrkmho.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtuksjvfdp.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gttlxcazwy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtdpgldlbb.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtslsamxtx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtukofnvop.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gteupiwonr.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtkklmdpdb.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtlwjlmyqt.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtokqotobl.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtymqnfjcv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtzqicibqb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gthftnirlb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtsdywtvxi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtrmouawse.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtxzakkobd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtnvtdesvp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtesurzbtd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtbvmhbcan.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtbyaulabd.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gtuoxtpcxi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtzeqpnacd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtyqkvirvt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtwkqkjcqs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtbyhlmbrv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtpfmhyxqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtjibgawow.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtgcdyiihm.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjrpxlagv.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtdyoymiwq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gtgnepfpzm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtssrkztwx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtdwsmipmm.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtrdosauhm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gttbqrbyfk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtpphtfynu.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtynpecepv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtcbjqdsck.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtztpubenf.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtzqtocrhx.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtvaozgvfm.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtadgclwqw.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtewipkrnv.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtbhbxidwk.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gtndnwoaln.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtidudnham.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtajipqqmo.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtgtbfxejk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtxagdyaqy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtvjogaaia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtzplxtbdd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtwchgmjen.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdmqkaps.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtjdrkqncd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtliyffdre.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtxgtbkrtw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtgvzoendx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gthvezzkgk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtjoehofey.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtecatyzdq.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtymjyogcg.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtgjhxitih.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtnnnskany.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtbxxdflsq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtnghhvqln.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtmxcimezf.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtyjftsfhj.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtkgoqqlzb.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtiwmgildz.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtlxwxnbqs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtyirqetyo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmaoptcb.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtvpwfxioy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtqoncdzrs.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtjohawexb.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtuqudgmfk.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtnsfzgeua.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtiqnibfya.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtidvdhgnc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtehrvzthi.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtnyecbaap.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtdayahofy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gttflkupgh.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtzmcmycss.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtatmzfjzb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtsjxvycac.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtbxdvjpko.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtnwbvrjqx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsyqbkw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtvfdnoojm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtxvminfbl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtyusbyayj.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtpljotngn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtfmeihhcm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtevndszov.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtpzoadtoh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtzseiqb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtucxeoexr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtfgpgmeny.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtqixzblhi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtioktovmn.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtmzpdscvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtqstviyab.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gttabbucax.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtlzskypiu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtwyiewkwz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtdltsvhjg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtlpterxzy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtlyveiewf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtchunhafl.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtrgwzuvvy.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtxtlbqwra.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtefsanchv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtdxrymixa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtfkpdyhji.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtgeqhjuia.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtdjhexvgb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gttmgewzvg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtpfuwujns.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtlkvocgqm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gtzzqurqfw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtrauttilk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gttvodckfg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfmeiczuc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtbluigfqa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtpulbgfkc.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtxqqpyhre.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtwvcduqsl.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gttumwfdrc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtayvlacnd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtjbuowley.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtssebkirm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtlrrkfniu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtwigdofjs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtkehehyjf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gthvabjzah.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtobjwnauc.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gthrubrunq.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtbaeogqyv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtpacsitnd.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtbsecjunk.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtzxydbcxj.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtyijhiclm.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gttlwxrtui.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtxikygsul.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtlgnjtxcp.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtircchxil.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtowypvldv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtutyqolfy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtptudeuwm.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtiecjsbwb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtxrjoxcrr.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvomhwtg.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtoanhqvvi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtgwuvaxrp.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gtzvdjnrle.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtfxhjhbok.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtxxmvrypr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtquuackoz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtehbnttbq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gttbauckqo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtolltoitd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtxfwxrgks.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gthurpyygh.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtzmcyncyq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtsubyqfuy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtrfnumrga.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtkzsuneet.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtatcsevqv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtfhlwzypw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtskrkaiiq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttmdjfnjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtwaxefypv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtadbxkffu.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtckosreli.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsgbnpgcj.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtwyozhgyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtmyuhsjrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gttgpofbzw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtyhfbmxum.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtidkhujjs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtidqkxwkw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtwlwmxgql.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtiqyinvwr.html


<!-- 参考信息 -->