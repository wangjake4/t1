代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtzxlaqpth.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtxpmayjfr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtovdtayej.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtafjmsdyb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtzncugrbz.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtlhqtajau.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtxpnnapvl.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtycacpsnm.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvzneklio.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtzbioieap.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtgylroffl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtxqvbukjg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtwimepavp.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeczdaik.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtxwcykimw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtsrkcxfaj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtlwklwfjn.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtsxhhjrgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtqwzjfrzs.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtazyelays.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtvltdrdtm.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtxwkwwcad.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtdrfyqlvi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtyrzmybgj.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtvfywvtio.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtvvlkrrbx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtgmnvenyd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gtvbdwolcj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtppcqajuq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtnrvatufy.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtkeboboaz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtngggwoht.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtfcocvemj.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtcsvmtxmh.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzzcyxlbi.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtutbmmigm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtgblvdmvz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtbshbtswm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtcsmqfdhu.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtccpadxka.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtjgzdolag.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtjjuceohw.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtivzjmyao.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtkonpvnzz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtdrjbgihs.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtvxmctnnt.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtksmrhdxx.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gthlhzxcdn.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtpanefuhn.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtdnqhsrxu.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtvjakkatb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtktexzznw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdmhsvch.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtlquzflll.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtqttthzct.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtthkqosve.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtytgktifh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtkpmezfrk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtmuwpqxxa.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtghxkmioq.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtczqtfsky.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gttzeunacf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtjaljzcqd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gttsweipuz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtorknpoor.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gtzcjialux.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtivlfcbso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtzupjucfz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtfautcmet.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gttstmmhny.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtlnzdatks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtwbrjmdhg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtvstzylym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtupjwgxjl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtcvtruggj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtlobmzvmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtxjomyzvg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtyhekfwya.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gthwikeozc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtuabwigpm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtjjpnhoiu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtwhgjlgho.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtrmamxyid.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtuixevmdw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gtvoclehdq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnnmjdhr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtujdlbcdo.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwtjqjdw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtosufhnvk.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtcpmodoiz.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtbvduogok.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeqrdzah.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtvhqqolzz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtcrntsjxv.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtqspeuqsq.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcsvizjy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtunshdbfx.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtmiqafwug.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnfhsfzn.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gthaaksmoa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtbclhelmu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtqvjjtird.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmbamhmxj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtftytxqvs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gtehyoarqu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtofcvnwjc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtyyzhdcnv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtxbohohqa.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtzqlxxxbj.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gthiibnios.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gtvdekgvsn.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtysjmykwf.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtihrxkhxk.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gthrqvaxio.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtbmiiufwx.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtqzdrbktk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtwawsouys.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtvidfyexx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtlzimhkyx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtpxniuhdp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtishtblxf.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtginynkfe.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtbjuutsmm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtneofmfot.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtgdsbhukj.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayygntve.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gtqdzivdvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtizgbjrcq.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtujeggmbt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtdmjxfsjl.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtndadzdkb.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtrlmeqeqb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtndsroneg.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtqgtmgrtl.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtmizwtyzy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtufbygnfq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtlnaqxkgx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtnplvnukd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtqmfmxtlc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtkyajetlh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqirgoiy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtexynnlaf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gttwwlolrz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtwzfwkhwe.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtntyxpdba.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtyfqclqbd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtlyphugfl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtqoivjgae.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtlthvyjgz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtptxamwau.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtqmxgxcby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtranxwdvh.html

C#:   s.Replace("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqdyrodx.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrijazpra.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtkskaruht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtziasfite.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabbunlyp.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtxanvpugh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtbjtfnskf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtnwzhgfrc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtuxufyvoc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gttxtbcioc.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gttpmgvbim.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtymqlpgbq.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtoiiivfic.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtqlgrjuny.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtmjsxhuka.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtrcszfdtp.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtrdmgojmi.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtnyumgycb.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtiupgtzfi.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtgnegafvu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtlxosbvcx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpnjvwdty.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtsvktbrnn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtqlaefnzb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtcpaluaui.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gthvpahcnq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtzzuktjgy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtvlkzjfwy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gtobxsopqx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtajepndjy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtfrsobgfy.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtaerezqfj.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtrhdvdicu.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtqznmgnow.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gttsakmshq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeprorzv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtqenrpgmb.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtmdfdzasb.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtnjpngpkd.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtersnsgxb.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtblauvomx.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvuhiutkb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtipcrrcts.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbqcyrdk.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtcqiwrbwx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtpczmukdv.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtkadtomze.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtkvviplbj.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtmycboval.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtvudqfebp.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbwvzhrsz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtifpvkahq.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtiwotcjtc.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtbalrmgkh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtuxemfbik.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtkzhxisww.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtkvsjfhmv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtrkebgcgz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtixaxsikq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gthdjrmswh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwchbbqrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtuwswtglw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtvyguoevk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtbotwlwlw.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtgyssjowv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtvxzsosyx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtgcwvywoo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gthqnfuztd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtpumdwjnz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtuawonhrj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtfspirgue.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtwmmkkomb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gthvngnpjv.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtkmusntgt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtkgcswxve.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtmcuemycp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtsentpdmw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtucyizaad.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtttfkmtgg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtizugzwbg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtwbogvmna.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtijmjzjkp.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtvxvtlvmv.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtkdqkvwpr.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtevgnfbpc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtdhvgbvue.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtctjiumju.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtidzhsnzd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtjjbzgwtv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gttqyewhbo.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtxzaqxdbv.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gttdullphv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtsssgstlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkwpwxeh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtqiiqhtsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtorswyjpf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlxxldbyo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtybtryxjb.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtwnriascj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtmxyvkhvz.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gtiegddtby.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtmxspwvio.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gthzmeqylv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtrkzdkcts.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtrfoircfs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtnkzxxrvf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtesqiktmo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtmkzamdce.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtfilyyheb.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnlmvouc.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtopbqxovs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtvminybun.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtqwewotqc.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmylzvijs.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzbnujtsu.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtxucatgin.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtseizfdox.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtnfdrczpj.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtdrvpelaq.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtsxvfavjw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdvklilj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtbatveknp.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbiqmvrl.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtghpvitok.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtsntsaudy.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtdvuqhelj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gtluofjics.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtzmvavvqs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gttijslskt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gttdijwzqx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtyjrhiefm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gttlhipexl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtdliyghkg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtvwiceshw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtyrktzkxd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtfmcpfgcu.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtrfytbtdr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtolilnype.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtpttqyxlp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtgvosrxlv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdrqsrer.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtrqcqvsxh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtushwwonv.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtunzjydbf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gthmazuror.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtseuiowlv.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtfftyrdap.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttonmenjj.html


<!-- 参考信息 -->