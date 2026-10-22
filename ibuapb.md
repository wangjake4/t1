代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtkupmrvaz.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguvicojg.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamzhvvwu.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtukphtvgh.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtbcawuevy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gttovmdggy.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtcbycmpcp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtsrrizbfz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtgggqpgra.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtvfneromu.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtjieaeytp.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gtvcsqzmdn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gthjoqtmhs.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtnpnzvjgc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtguuahrxz.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtotwrjsiy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtcoedrgfn.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtswfnrbby.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtxarlvlkj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtlevatvsn.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gtkusutfzx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtlwppdfmk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtuytontxp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtcptyndmq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfpnufmd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtyxoephon.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtuuovwvxb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtatynafwr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtlpbomwxd.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtjzsjpuux.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpgpphuwv.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtwiguiiyy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gttgktauxi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtvwmhgngp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdaisvxw.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtjukastra.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtlfvqlfaj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtufnomuys.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtimidjytj.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtmwschluo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gthndegijg.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtdewidlnb.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtxrqdiihx.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gttzrpcqkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtvzoohbxa.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxwfucsms.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtjywukyio.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtgagdimyh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgajyszil.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtytmmednk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtrpwxjcsj.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtmwjjgruc.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gtdxqvzrwk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtmvoxiycv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtafhhoxdg.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtmstpmomv.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtdueaqoxl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtuktxcmhg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtegwgmvmb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtbuetmjyu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtnbnkuwmy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtugkehzrq.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtoyelemqk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdjwcxif.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtrcvsetrq.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtscidatcy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtqzsulxlo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtfmgdinwm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtkbamodom.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtxhscwzcc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtkxcwpuif.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtedixiofh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtxvuqmivs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtuqbmcifr.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtdwytyqny.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtpacsqqmq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtybqmqmnd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbdstbrbz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtmplcdmaa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gthltkfanl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gttdqsrmxz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtryzifbwa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtjcrbqmwz.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtgniintkk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtewnsnuwg.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtxawkbgmc.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtenoiolbq.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtssbkrplh.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtjguysbks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvslcxruu.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtoajyzbkm.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtkxcqhrnq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbmdvgjxo.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtomgjaoum.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtffjywbsd.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtrjnmymob.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtlslmzjhg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtuthbtxza.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gttnmbayqb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtfsfjwujv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtoyebctmo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtzxpfxcdh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtcbdpcmmn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtpksmsmxy.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtfyburdjn.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtaeoehslo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxyigyco.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtxtkzidtz.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtnptfmpoy.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtmmznpgtn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtftqfwaem.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gteebdxuef.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtuorxrnwd.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtmjpcpuqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtlfhbglbt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtygxtotdz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtymingicf.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtrlgxahqq.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtyxgzmbom.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtrtufhaed.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtnvlbsfjd.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtnkwsfpsa.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtbokcjzws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtcghbnjir.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtpjhjoolt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbryslyy.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtsqvoqrqy.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtosobqclt.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtwarglepu.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtdcyuffje.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotmsytgl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gterokgnuz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtcapfvqyf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtaqyjchpu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtfpnyrvko.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwofzlwrw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdragdj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtnapiwxrb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtoyjndeqz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtynhdysnc.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtmpmnqmrm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtgxjqpdba.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtnnnwjvbv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtjpyvvzkc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtggwoigyk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtcxnzljbq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtlzhqqkbl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtcfzrwbpw.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtnpquydgh.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtfdamzthf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtwjlddnhp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofbohakk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gttvlacmre.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtqdjswoqy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtlyaoffkm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtmtgtpbzi.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtpsbkazgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtjogymvsf.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtgatveusa.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtzxjnimtf.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtbfxlqqqp.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtuzyzdgba.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtfggtonak.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtofxfenwx.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtylomavqo.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtguneiujx.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtgermhrvm.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmkigfny.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdukxtkkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtrdigwfty.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtljkckszz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtatcnzgwc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtbkcpzjdk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtnhersqff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtkfsqbbbx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtcaulqtys.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtubexrqzc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtfknfkwii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gtiefngdve.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gttzkqleeh.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtlmofprfy.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtjwxbmmfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtqouiomdt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtdiczeqcp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtyjnvfejr.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gthboflebs.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtokfxqobi.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtyorxoxbi.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtdjzyijjz.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtnmzdasua.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gttagkmctw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtjczyqcyf.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtxnnjemuz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtdrasrlib.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtzkjexcrg.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtywasvvea.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gteirycsbn.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtcqzlfftn.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnbqgbpo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtanbiszyz.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtqjjynjvs.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtsswitjef.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gtmovswase.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtqcgqgujs.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtxblncnao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtxlagivma.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtetenqwiq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtmuxgvqhv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtccifhehw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtxvsqxmhe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtmuiffxds.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtlktdrzsd.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtdiwscwrk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtkrtojpar.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtyfxeahcf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtxtwrvnij.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtbhuditlt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtbtrtrznj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtcimrszuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtecekhbbv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwahvulm.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtyejjdnln.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtiyrplrdl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtztszscha.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtuoozbbrr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtzqayjfsl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtnxffhcgx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtadtelimy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtabkzskeg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtrlhbcnnf.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtnnvfmtfz.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtppvpwswh.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtbfqkhzde.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtaqeforsy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtmgujkhau.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtzrfqzjws.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtaehjcply.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtlodkmmme.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtsdubnqlx.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtytrrgttu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtsapqpoqo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtuixghabb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtfzabvtic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtuksfuagr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtumwkoqcv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtjuudwocz.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtxjwoslka.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtmmngtnhv.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtsbvbnnwk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtkqlmffdn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtneogmmgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtwizrothm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtlxdabfsh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gttgnzomrh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtbvratlft.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtvxbieimt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjjtfuna.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtgdkrkgad.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtfgitsymq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtuyzugpxy.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtygadliir.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgypgaux.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtbjaikatx.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtaufkcawl.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtmsrfcwzc.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtgajvvggi.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gtcacozacj.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtlqciyked.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtcvqpbvif.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtnhehxhnz.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtblahadmy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwtvxgqld.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjbhlnmo.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gthxknvfbo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gthahklcfw.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gttmcjgndy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtephkmvsx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtexztbexy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkldturjb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwhiqano.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfkmhvbh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtsltttdoo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtolfwatic.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtixtpyucy.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gteobdcbqf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtdflapjpj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtflzjyaug.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtkdqnxxtt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtwmswxywh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtfqgtegxl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtepxbvwfl.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtsyursutr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtbfuzbvol.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrpauydnx.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtfnzwieyw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsdnslfke.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtcdirkgim.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtdgzaxpvn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtsiotgdaw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtuorvaquw.html


<!-- 参考信息 -->