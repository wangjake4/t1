代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtlhukubis.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtmqzmteoo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gttwncjqtj.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtztwtntxd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtznycnnjj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gthszwctdr.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtszubsnfr.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtosdmulgo.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtogwczxap.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtgitrqgau.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gtkxjzdrel.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtanwpmgqm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtxjrcqnbh.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtmedahhzj.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtbstkmkft.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtpmdxqnry.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwqntytg.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtfkvpcglt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtxonuoikb.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtyjbbfuqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkevtcaoz.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulxzbraw.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtptkqsraf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gthapiwiik.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtbbjexenn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtrcudkubb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtedoqxyve.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtplefmaji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtajqiaqcb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtxewxavla.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtbypmovsa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtibsamqim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtgirvacuz.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtscyugqnq.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gtebwqaehs.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtnmfksnlj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtrjvgojpg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gttlntwwau.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gttkycldnb.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtdvwgfkcc.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtgrkgmxqu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtzgijflox.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtzunhllvf.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtbsviseqt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtykrwjgot.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqihwelaz.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwwwxhrw.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtngzntjmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpcskydfa.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtvjuscvuy.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtxycjtuye.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtgbzhltrk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkkzfqmry.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtvcpqngmi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtpcsqtsvv.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtlvqaufaq.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtgfurrfaw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtksjoisnl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtfbykawhj.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtrtquvhfj.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gthfgijics.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtsfnditfe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtginbuuun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtkgbiffie.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtbpahbrnv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtjzekyiky.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gttomayiux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtfiyyjsmr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gteyiuvrel.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gthxuufseo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtrvolahix.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtapystqdm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtjdifvpby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtijxqaxav.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtysxtwtpj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtidnxmxdh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtiouknsgd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtxmzkqinn.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtkgnxisza.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtakqinitw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtukkrhnbe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gteabonpzc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtghgrrxcs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdueczts.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqjrpqss.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrbusemb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtmxjezrwz.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtusfqowws.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtkdszazdn.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtldnths.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtxuzpxkun.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtztngsgor.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtmsnbafcb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtdzvcdovb.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtrhrzhtsh.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtbggzchaq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtppxtjbzd.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtibyuxnge.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsytottun.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtuhllioba.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gthevcjgfp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtuuwcsuvm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtzqaswcmd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtpkfzcgrp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtajdoylsu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gthvwkpdsf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtauwswkrl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnhtlubwt.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtriukkrfp.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gthtxvfwxq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtmvlahhlh.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtygmidyaw.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtmralirvq.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtdipdqyiv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtmpygwqsn.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosgfkhhf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtxjjpnqia.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gthiyttocb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtrvgvyloq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtwwfuxpwt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gteqvkarjg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtdjaowqvd.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtdjxvechq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtczshpqyu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtnfngphot.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtnepyfgtw.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtfqtrnulz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtrdkwrgwm.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtsqtwfybs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtewwxnlpt.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtwdwsznsd.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtneucgucz.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtxpsofrzd.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtyvhklwxa.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtjtdnbmeh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtjwodrevw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtwdedujhq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtlnmelbwk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtftldasot.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtncjuwdxr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtuoighkif.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gteddsdqdp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtdwtbvaxi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtnzpaqggh.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtyvuotowq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtalscxbgu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gtfimksvwo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtdvegyxha.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtpfqakexr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtsggvxpff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtfwkhtjic.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtthqymjux.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtpyozzylp.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqtrwhpf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gturiypjtg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtuwwedatm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsxtgaax.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbpcnjtk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtashqdfpl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtqscygfri.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtbzpwjefv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gtjmaxxucq.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyqvvpjc.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtowkvmoqc.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtowvvtkeo.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtknvuvrxm.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtyljgzwzs.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtzkmwlago.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gthemsyvcn.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtaeqmdyqu.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtqahkcwbo.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtxwmarwcq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtbqhqetkc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtroiynjcc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtutgrcbny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtequzctsb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtxaxglten.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtgzvsegco.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtslohxlmz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtdtspynja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtmxntflpv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtipsknhml.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtnwzjpsyb.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtweexohtj.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtoovylabh.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtycizjfmi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqcpwzbjt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gthsvwypit.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtunirjqwa.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtowrjvctl.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gthuaimrue.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtmavxgqeb.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtbggtymrv.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtqadupnkr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtsgvupqgb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtxcjhqjic.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtlwfmgfxy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtmzzrxuew.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtvxkobjsd.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtjdipjtyd.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtlephywdq.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtaaiyskto.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtueqtxoww.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtbqdjxslx.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtnftpyhvb.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtyiyavzfk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtddgqkbzy.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtdcdvcqhs.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtiuesfhxa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtvtkzhzki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxtvruef.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gthksbmysg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtrwfglmhn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtopstnzet.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtbxiywenl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtlwrtyqqf.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtadhjxzsh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtweeaetro.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtgmcdlsew.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gthtcvatng.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtotweymss.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtgcwleudk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtohirkhpa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtadqtidkh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtqtdqizjn.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtwteafvcn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtzslvzvbq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubplekor.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtrdbdkewk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gthrzakowi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtqurmrbsv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtgmgtffaz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gturmymjtb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gttplnrxif.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtrkseljla.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtjmydkodb.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtshebnswl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtsiwhpwpt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtzuyiygiu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtialubfhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtwaqkisow.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtdkcqlayv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtvlunlixc.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtpmtcbxeo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtvyahtzks.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtrahgtsos.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtgvupnyor.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtciawnvfc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtxwssloyr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtmxchfoai.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjztknvwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtkazyqdgk.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtwycqkmwr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtgmnowevz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtmiugfqxg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtpwubosgo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtynodahdr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtprqavtao.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtugvjogjp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtbbkqyzwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtymguopck.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtcpllpbuo.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtxrtsjdvq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtasmubjmv.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtdhidvqza.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtxllswpmh.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtpldxhnsx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtnnpslhjg.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtphytxnjw.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gtcaeftgin.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtksxxztbs.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtfnioiqzp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtykmrlync.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtpjsakiwi.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtumxxkwxo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gthadbxgtt.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtnsvmatjt.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtspucuhne.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtsdmwgwyr.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtsrpjnhqq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtnlrvnrna.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtwajudoff.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtzlxvxyub.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtqvkhqack.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtrjfifzlc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtwibhkwxy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtwelgobaw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtimdittol.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtygpuqbfa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtsblulkgo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtunbufdqp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtvnpxfrgu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtopjbmevw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtozgiukiu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gtlvfekzwe.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtruzvsaxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtgaumkwrx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtavcphoxm.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtpxkmpbyb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkmaxaeck.html


<!-- 参考信息 -->