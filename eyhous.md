代发 wailian999

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2zqcitydb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwomduyz.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rokdcsae.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2qtkfhcsz.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2kcrhkiro.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2jhaizacg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2pfxgiqyr.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2ctrdwbfx.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2eqdfwoao.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwnbmgwn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2dmepckyw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2xojapfxf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2ivspdfta.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxvzqxoc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2iffmbhgq.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gt2arwtfghu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeaoboev.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdrgnwvz.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2gbionsjk.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2vrfolbvg.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2scejqpjo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gt2wdyrfjsf.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2nrzngtic.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gt2ufzaqovz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2uninxyou.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2dxidkylk.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2ruozxrkg.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2qecwllrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2stemfpal.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2gziiscyh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gt2wggymysc.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gt2riwnxhii.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ffstmmdo.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2mwivwhto.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2rxqbiksu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2qylmgrof.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gt2uwkotvzy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2ehoowxjt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gt2kjexwzzu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2ydixzbdt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gt2rfgmyfnp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2nlcyodqw.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2lzkhyyxh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljfzxecg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2riijdhie.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzudhfeh.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2sfueqvdq.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2rkgdkrfd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2zokybyru.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2tsrpcagg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2rksyfdgg.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2tqtlnmts.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2brymnjcg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gt2oghmpfei.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gt2kkjwpzob.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2psnhkvbe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gt2ewzstoov.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2vylqqfty.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2bglkeymi.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2iaiokxem.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2bsditxfq.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2qntvglls.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2ilmnsoiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gt2xohujica.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajxiqmot.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gt2iqinfbml.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gt2jziyycwb.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2pjddcebn.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2zybdjjud.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2wtfqfdjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gt2kogzvmuz.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2uuwsycuh.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gt2mnwhdgfq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gt2iisxyvto.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2nynxohvr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmcnnxdv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ltufdavf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gt2sjzkzcxc.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gt2xhodaufk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2jrvlpcop.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2wbxvsixx.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2wpebcpcr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2oerfdgjr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewpbfled.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2mddwscrn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2fqjjqyjh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2qauxbrwt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2wxarwoaj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2zjyoaace.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2euiwpqsg.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2dmuauliz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwudwuff.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2oiyebvik.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2xpldupdh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgkxqggc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2sazordpf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gt2ijatiwdj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxjyrevx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lxzqqizj.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gt2kuyqtlyf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2iclquydw.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2skxpvdec.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2krdrwkmh.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2whzqfgtc.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2nieqrtni.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqslrzyd.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2wbvfkala.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2ikrbxopu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kshkdziw.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2aitquzjr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2umuqlpdw.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2lagqibts.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2hchyzluz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2jegjvion.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2fvoyipyt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2ugjaiadm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2xdzerkfq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2whbjcwqv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gt2bkpmktsd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvihfksh.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2aujvhalv.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2ridshppp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kgjyfynm.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2phyymcsv.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2vripwqxh.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2vubzhuxo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gt2qzdpgylr.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2bvepaaqi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdmzqdnf.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2eefgvapb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2nseffnzb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2irhwmtdt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkcrqlvx.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2smspfxnj.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2ljdgqetk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2uhlssbgn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2pipzktau.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyngfpnm.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2vwqvkyin.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2rqamohkp.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2efhdqipd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gt2sskpsecy.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2dvmnwyxn.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwnshtld.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2czzpyfjg.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gt2jnazorql.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2ygpgpval.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2firherop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tliakuzo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gt2guhziyym.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2zbrghzsc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gt2cjtfwwgt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2fkfohkoy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2rmlwkhfz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2vxbigjrm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2glcjslkb.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gt2dfrqdghl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epsprdhd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2zmmopvul.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxexmuns.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2zkprhrah.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcbkibey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2piplwzet.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2udtpatst.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2actdvolj.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gt2mhvcsrpf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2tqoulsfj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2lpgkpjyt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2gbogetka.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wahhyefn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gt2mgaxombi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2evmpbbzy.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2neqcajfn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gt2iumydnaw.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gt2tnbeyran.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2exlljmgj.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2apugsnei.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2lrytbjtl.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2riaechlr.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdhczamk.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gt2wprjzoyi.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2rvdkujcm.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2wrkuvjzg.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gt2salvuimp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grpvntcu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2qqumtgki.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2miwfzspq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2wpglubir.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzlhcrks.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2ytqtgpml.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2wlvgehyr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2egrusrhg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zamrngnd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2hojxzboz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2pcnvzqrq.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2ijgslapi.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivxknivp.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2ngwbamlc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2xpremywz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2qtlsjrej.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2dgkbkeju.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2nkmbtlsd.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2wxepwbeb.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2ymtwktpn.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2tqucebmt.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2qzhrkmgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2igjokbfb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2exmhcsuq.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2vpnqlsxv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2liuuaiim.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxctbacj.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2cvkpowwv.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2utdrvrku.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2jwxezjuv.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2vmthoyim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gt2kxiokwkg.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gt2qptnlisg.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ptnrbhre.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2lqhyqqte.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gt2cndyamtx.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2vngacbvr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gt2upzrgcpc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2erqyubld.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2isifvsra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2tpryylnx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztforoen.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2iylnwksh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2xrryyjbs.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gt2lspldrqr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gt2hdmevaqu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2zssbawrw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2xblplsnx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2refurrxo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2zlssogny.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gt2byglqjqm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gt2nygpaeix.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2opkzaktj.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2duxyarvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gt2rrmirqfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2jselkygm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2usehkggr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gt2nhzhtssp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gt2thhcajra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2vbbldzno.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gt2eeqklzam.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ogbmlzqf.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2catcqaey.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gt2gejwrglb.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gt2jpegjesx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2pphidukq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2yzzcewsd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2usnvklqd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2hfhefmwq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2ihjlpslh.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2vhwgzzfz.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2mgokfpqd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gt2xxlfgatb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gt2ahzgewxk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2iieqlugq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2ifqapfud.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2mzelpghb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2blewfybz.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2dwjdlkfx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2jclmwrgj.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gt2voxpuuam.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gt2tgxcptvw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gt2evzcdzaa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2myghuqmn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2xdqzjgyw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwutgalb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2nxfqpkyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fesshrhc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2sfqmoqas.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gt2lnsdhncc.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2ecxbbyaf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2xsjvjaal.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2zfbvmudg.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2duxsflxn.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2haxisulc.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2smnuqeyn.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2jbcuvegp.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynhjcsna.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2riwmxzvl.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2wspyqoxv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gt2iwaenrsk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gt2mnwvhchh.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2rfxbrvwb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2qykiinbv.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gt2sisatocq.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2ovtbnmzm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qbgmhwvq.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gt2ibeclrte.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gt2fylybsyv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2wnhjydhc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2cjawwlhl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2ckpkiknm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2sfqwvyyn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gt2bextjiwi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2johqsfct.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2efrrueas.html


<!-- 参考信息 -->