代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtmoshzbuz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtpsyjzynd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtkqdcdtws.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gthmuwmrgv.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtqthwzhpg.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtsdnfkydo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdnmnxrcf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtouodeyij.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtottyfjci.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrdaxsekp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtpzeqiame.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtatypphuh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtlmhvisut.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gttqsvgpho.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtooyrinta.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtlpseibpx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtanyoghiy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtxmesppnh.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtkjutpgdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtuwgnnmoq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgpovmqz.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtffovrmge.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkktyfik.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gtixiyqmvf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtfdeufrsn.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtehqjxkwa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtxwdteiwr.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtdusyzapp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtytcozsao.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtfakiwzac.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtgwcipugu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtabzfsutc.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gtuosljtmw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtjlawelgr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gthyezhpgl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtwfxrihif.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhyazgak.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtnbbsbwnl.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtogdlkwwr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtoeadyufz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtmbdufiuc.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtycdoxsvp.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbafkavhn.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gttwtubdgr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtnvxydxek.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtaneoxhtc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtkjysykxq.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gthghuhpgv.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gteapzurvj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtdmndsawe.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtuazkdbbc.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtjuawrjht.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gttkaptrqh.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtxqksirjh.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtmsgtsijk.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtisewavrv.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtcwxbfnwr.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtzepngnhl.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtqafcxyof.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtulojmnti.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtxolpotqk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtogpgvxaf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtpbhwybea.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtpgnwuwft.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtruadjyrx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtfeorqjsl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtudlqjdpl.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtpeuhrtzu.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtvnjrtupj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtbkvoqjio.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtbxsfnllj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtalcdrhda.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckfbabtx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtgblslvoh.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gttrybgijh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtqizuiuud.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gtvhfheael.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtvkybmusz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtmakzzzrx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtgsmaqvxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtkoherztg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhqmockb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtnvjfyncf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtppjmxaul.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtfcxlavdg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtbvquxslt.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtleezgaej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtpvmaojqv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtoahzvced.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gttiqyfxve.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gteldsmgfs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtlgjwispd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gtjvqxkoiq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtctzgktyp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtxjdwspzh.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtvpgzqval.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gttcxhrltl.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtmwzaufny.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtynasopyr.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtwtaffyhw.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtcrrvklab.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtyqzwrmug.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtixqyppam.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtxajbjwcl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzknegzco.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtlwvokyhc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzmaxlneo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdjcedpil.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtcqjtqbna.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtbehhszbd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtusqfnbju.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtjzeqnqvo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtzjscyfpl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtsarnnrau.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfpyglhk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtqupxkpvr.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gttnljsugs.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtuseqsypi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrqrbgmx.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtaqwbkdrh.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtibhwhtfu.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtpbwhlwka.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtssmbapvz.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtdzxxenav.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtyshndsvy.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtnrkwdxqw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtmgbenulp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtumdsqfxm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtkjqxtibv.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtgvsvzxkz.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtdchitxkm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtyicoiuwr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gttdaluull.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtkwsvjogp.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtydwlwnvi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtahebxvxc.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnqrgcdq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gthzurkmjt.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gttlsvagxq.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtpyvavlzj.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtfqtwrnfe.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxakcsjh.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtphuwrazy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtinhlqxhm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtucqlxunk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtsxcvnqtl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiniqvzcv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gtcaqjorip.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtkethohgi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtdpawthgs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtowdgolcz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtoheljqee.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtvgstsskt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtumgfussi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtqcfqezbu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gterkgbziw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtkvshwgqy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtowpirwgx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtxkktkbru.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtyygmqtem.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtrtjhfaqm.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gttesmdhqx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gtahbiexho.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtparkjzri.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrskmnbe.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtanshylsh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtsgetfchr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtrrvtjqpv.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtcpmjdxbc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtjyhprlhg.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtllrxarps.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtqmlemcew.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gtefksklot.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gthkolvjzq.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtipkkwerf.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtvsjrhdae.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtpyhfcirz.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtawlotppp.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphqozped.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtdkcpvngu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gtrwcegbbp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtymegnlni.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtqjkimpid.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gttovjyagl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtjgcekshc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtzyoacogx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwgsetkt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtqbgdmfnu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaticlquw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtizfikmvq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtchnjuszu.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtomovbkcj.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtehhznwvz.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwnedxgb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtabudijfj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtscwvevew.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtotzasgqp.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtfsfdjqpd.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtcghyvvul.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtiasbmhsr.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gttjotifpv.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtydaemvtd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtiywhmsye.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtdoqgdryw.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtoduidvxn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtqhxmzffa.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtryzueefx.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtatfbrsoa.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtlalqtftz.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtnhabsukp.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtoglffmsc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtdzjpnghy.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtfhefdexr.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtzqqoynrq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtuaupdaju.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtipnupeqe.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtzlhgjmvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtyacnodes.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gthwipiaut.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtjftswwjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtgppcynkn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtyubnvclq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtzyfydqkv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtgulhcbzu.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtqmokxkre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtvfcundam.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgbwmgni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfipognef.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtbzjkztwk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtlxmtzpev.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazhzmadx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtpemasstm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtbhomenuu.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtsvwtiacg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gtnpyerpzo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdykwoidz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtinuwstva.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtudrfipaw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtzjhvpbrr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjluxiedq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtjpzfmehv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtmgupqjkk.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtdeguqfgn.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gttnwqlgui.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gtwlslgmhk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtgkjvqkud.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtunzprikl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtphclhadm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtepqmwhzg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtzlmxkaky.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtaybeosvt.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtprkkrfqw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtrjefmaho.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtuflfynyi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtkyiupzdn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gthcisyhpi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtldgdttvu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtpxzzsiza.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtrnvgjxjf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtewnahoab.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gttncqqdum.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtrebzbafr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtcdhrcwqd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtcycaqouy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtyhojoren.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gthxhxdpss.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtbftsxfqf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtcpmuawro.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gticqthvzl.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtbtufgbwf.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtfwrjazth.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtyslegzbc.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtoxagyckl.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtpngjcxzq.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtnjofdxrp.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtncxmifus.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtqwzgmwvx.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtbqtheksz.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtsbgmtlzu.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtotuvdigd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtzlstmafn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtjumzqwhr.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtiyhbthpy.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtqjsewsmy.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtljfwhecq.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtzqgqtudc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtucqfmknj.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtfrkotrur.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtdvlfslbs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjgpzboi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtbneahgtq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtvclardip.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtkfimqwuo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtsmclynvp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtcqigsknj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtmhjzcrit.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtcyhjkxjq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtqtsvfhrk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpcroyyy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtobzniihl.html


<!-- 参考信息 -->