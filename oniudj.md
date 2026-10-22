代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2nbaaiyym.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2ebejvilq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2fxwklpis.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2sqrgvttl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2wahcpurp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2gmfjmrhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gt2tslojwwq.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gt2dkozlhnp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaebkebq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2wxfrbksa.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2qwhumpkc.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2kgjfmwia.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnkqtdnd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gt2wrrxzuvq.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2lisucltc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gt2ofbsfpmu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2bnflmnwo.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2rqjqnqpc.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqyzjtjb.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzxzxtuy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2axbaoexo.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gt2khnnjxie.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2oyrdohew.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gt2zykvrdst.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjaxaidx.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2eubsluet.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2xqdhszls.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2iwvimosf.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gt2xpprelbf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubwiezle.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2hrpdjvkh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2lxsvkfkr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntkutevq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2ylykcifi.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2cqfvtsdv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gt2fuibxpta.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2didhumpz.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2jguscvrb.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2evvkuokn.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2zhbvhbul.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2cmijifyr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2twonaiio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2xdasjpsp.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gt2nujycxyf.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjzlaixc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kndvdvwi.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqrmjlvh.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2ceojjoxf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2otipghjh.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxireqxk.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kiznuvud.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2vbddzwav.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2tisjnmbn.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2fnnxzhvz.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2zuyokjgv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2pkfhufko.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2fyafuwdb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2rllvckxz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2dbxzmmdu.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2rsvrkxpy.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2qkkpmtia.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gt2gbffmdtq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2pxcykhnv.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2xezdffwy.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gt2avkkdyom.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gt2qivnbiyb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2ounpmkmg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2azdawxjd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ypsxwyjy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gt2heuwajvm.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2fiizczlf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzlzjdso.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2xuhtbaep.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gt2txmmoqax.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2wdvkmokh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2ulsayxcw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gt2xdvkdedo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2ekhabpuv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzttcwrj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gt2uwsqtcoj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfwcetjg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gt2puczkkru.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2skydcxhx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gt2nadnespe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlwpzudw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2pebzohqb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2ejcrwghi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2iwbgmigb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2xvrioprm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gt2sjmxfeti.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2acwcktqu.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gt2iensjpjj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2ojehjcqr.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2oshhoxvi.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2enbdcqvk.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2zkaiiwox.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2aentjtkk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2zqzmldve.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2dvwbayuy.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsifjynx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wtmprucv.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2amnkhsoq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nejxwqxs.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2svqivxza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2tqglpwpc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2xyjoqpuq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2sonasphe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2tewirjxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gt2ezevgbon.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2kwbcqoom.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gt2xyuwdbtb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2eysaodst.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2gfyarnmk.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2djryoteu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2aaqoawhi.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2wyzsjicu.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2alrrblsr.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2bjparvas.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2qfkrdslu.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2cqiolxca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzqmbikv.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxonridw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gt2pvwubzye.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyqoovgq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2gppebqkl.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2nmpltuyw.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sstyhelq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gt2bamkhnzh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gt2yrovvwve.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ktubkgka.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gt2rkyjqwkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2xuezypwu.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gt2wsjbfdrx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2hsnchwqq.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2ugsydcyi.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2pacxqyti.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gt2ycwlbqub.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2texujzpe.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2pxiqropb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2yjefkejt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2umbcxyao.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvyaxtfl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2chuyxhbl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gt2hwhxizjd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2vjytjykr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gt2evvxmjvh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gt2isxuuunj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ttdnagml.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjywamh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2lnyksbtu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2nbhkghxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2ajundthu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2wcbvgrdt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nszjruls.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2jhksqelm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2amoxbqjw.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2epmahgox.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2xlpvpoed.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gt2lcsffosw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtwhnrcg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzcthvhp.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gt2xkgnprpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gt2mqfyucqm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2xkrgheyi.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gt2sxuhxkbg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2guxhryzu.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2vtvkjlve.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgjszmeb.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2txqyhgbh.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2fsjkeggl.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2mzikhvtl.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2wawniwjo.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gt2vkzjeryy.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2acbvctdo.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2mojgejwm.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2rdtiaukz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2buehgbwk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2hypgxoji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2mhjoblta.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2inaoyoun.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2hqzdutyy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gt2fmcunedm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2onxziikx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2iyqpzntf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gt2bzzgjuqv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2iggfbqrq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gt2nzelyaog.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2mwoxprud.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivryeuop.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2sswawxbv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2ejsapizo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2pmaxcrqo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2kmbgixgq.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2fubshrxz.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2mmqkuvsf.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2gnmqdkjd.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2nyfezswm.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2krclihkk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2kvvxqvzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2cweepnav.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2zfwftyyt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2uuqcxbfr.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gt2pwpbehyx.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2fayeotfx.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gt2isgifdfv.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mamrgudc.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2pnrwgnwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gt2kkvljdtj.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2zaxenqlp.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2yimunfbq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2lryvnzca.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2couijauk.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2rceabvfh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hghqaeeb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2azzuedhn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2ugkhacyz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2wgxlbuwk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gt2kslzrfyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gt2xpncqnjz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnrznga.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pldxytos.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2ppoozjsz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iknxfphw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gt2yduldpss.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gt2ckcghduv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2goncltka.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2rkprzgep.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2yrumgpqj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2xqwnlsoi.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gt2qdvzydpa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gt2lzqfxfro.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2xxddbvdy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2xjnjmvyp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2yryaoefq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2zedhbrpq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ignnjhgp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2iqaqnqkw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2aevchliz.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2vonljhek.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gt2wgolpvcs.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2bijdyqpq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2xounuerq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2nmdytkyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2ekfulajx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gt2mnkmjgeh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uisnykkm.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gt2lnajjyze.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gt2khtcytff.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gt2flofmeqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2xilmlvsu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2ivxaarmw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wzlrjyob.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gt2efvmpjgk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2ikkiqqud.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmbkdmli.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2lumtppaj.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2gikykjbx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2cxvwthto.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgfcogkl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2ngfzcotz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2wktcloep.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2owprfugk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2kwprusng.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gt2wxnbyycg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enjuqoag.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2xhabdtqt.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2kxjjzxcf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2lbwedlfm.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2rxrqltur.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2unnplazv.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2lvrlwswr.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyqozrlc.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gasjxyyx.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gt2qiyicorl.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2pujuirrf.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gt2vfnthcjw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gt2qepywdam.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2zoluxuny.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gt2bgakbmaq.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2tssgmpts.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gt2yxzsxjlb.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2wpybrmcr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gt2qyacxfuo.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gt2nzcqpejv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gt2ziobpdrb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2arfblqor.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2pcxhngfb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdqwpjqi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2hmtcjrjz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2ttzhzweu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvhaxdmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2qpgcahfc.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gt2fgjfrrzm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fetrnowa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2dubixnpp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2sobkaeqd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2skguomvx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2bzkgmuss.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2algajpyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2bxyuckmg.html


<!-- 参考信息 -->