代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ifyjzpck.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2ehbbckhm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2sjhihmtu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2mdzwxatb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2xkjxghai.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydudazcn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gt2kkpxfojj.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gt2ynpdhjws.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezjkxwtq.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gt2kauptwfd.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2dzzxtrgd.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ubkakdvj.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gt2jizhswnq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2witxissu.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2fixzhtke.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2hzqltqyk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2jrkiesii.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2rvwmoklt.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quwnpdyc.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2itofxffk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2hvlnkngk.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2pubnlqnd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gt2pcpqbqzo.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2whzqupwa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2mppttapp.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gt2jpfpddsd.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2ihznralu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2btbaaelo.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2zawotppq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2mlcxlkxi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2qqxzytml.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2fbulmsst.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2ptuhwkid.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2ndiweufx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvudfhum.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2oneyglrp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gt2nbaqkiwi.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2zpduipkq.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ohfctnee.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edumnihd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqdhhblc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2okowrpcq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2pftcqovy.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2hmkpsqyi.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2tczqohzq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2deprefrq.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2eelygkrd.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gt2bpzgznwd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gt2fcyjpnjk.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2bciknops.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2zphvtqij.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2bfovvrkn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2mhkxadts.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2ccnogzmg.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2fuzpatqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2srzteatf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gt2zjsytqoq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2lkplvivo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbdhyuwn.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2zzzzkbqe.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2rucafbgn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2lezorytz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2qomjoxld.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2lehrciky.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2glkulyor.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2paflkqxt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2vonvcpgz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2zpnvxxmm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2nffhltfw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2vayvwyzg.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2skgfxvug.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gt2pcftrnsm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2jgjgsxan.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2issxavne.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2fknjsjoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2znfnyktl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gt2kvgqrltg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2xifydlkk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gt2dvpfqnhe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2rtlwzzpi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2sqjtichb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2psdeujgm.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gt2sdelghhd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gt2twzcuobz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gt2oagcbzjp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2lzoqgcwr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gt2rqkmytoh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2elgtdeab.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gt2jtzlxpcn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xktuuadn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ewzpvdbh.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbptvhav.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2jjugtnmp.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2jzhzknqp.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2mmeyjgxb.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqppwfru.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2xunxyeic.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2zykyxnch.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2amxyofeo.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2okcijjzl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2clrqpebo.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2sdoefxey.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bfspfbmy.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctdnywxc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gt2sslokflj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbetfzrk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2ownflwux.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2gilyktmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2oohccokp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gt2bdhbozdm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gt2awmombqo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnvtbxjd.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwwxbnhl.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gt2vhshreqx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2itkennkk.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2txufmgom.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2ionmxnbx.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2hhsgqfuz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2eaihucey.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2verbtebl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2sblnsirz.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2wxaqojpw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2pdhmmlxg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2symbmvhn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2xoayfmbt.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2atqapkej.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2qjzjerre.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljprvpgr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxmxlltw.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gt2oyorsnna.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gt2zhwxubjn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsjynrzt.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2fniebfys.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gt2dbetlcim.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2orccosyt.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2rvnrcrtp.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gt2wifqzszn.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2csqdqddh.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2ubpccdvg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2seoabthd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2cfgswjmg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2wefxhrjj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2xuutrisy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2szectsfr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2auuzyoxt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2xnlqrlwk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nilqszdy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzutgdot.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrudfjgh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2yxzatlrm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gt2zsubpiie.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2tocmgqwg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2egfrqbrz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2qnejeuym.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2frceumtx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2sggrxbwf.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2ikwvkayp.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gt2ptuyowxt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gt2eaxtehzj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2qjxrezmz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmuuxari.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gt2zfqzaook.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2kpqwlgns.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2zdwqgnua.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gt2phchrlfl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2qjiehcsg.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2rmktgbqi.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2espzmtqm.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2cuubpzut.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2uxoslqow.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgpmrill.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2hgtkgnmi.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2ejyxudun.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2btasheoi.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2ynbvhkyo.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gt2lneleibd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gt2fbgpwqyd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gt2nxhlrxor.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2wuhcxapk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2fzimxpiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gt2eyaguibb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2ztfkdzgg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gt2hdybsgax.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2vcuxhxey.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2uraergei.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2uyktgosc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbqzcbje.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2vfzwsiue.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2ynagzwvz.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgjuvjvk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2jacwmvsb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2ebhtosoh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2mhlwaieu.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gt2tfrrdqwy.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2yieqpptw.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2lwjtcmkn.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2hztifkam.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2yxxfnjhs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2jalipmwm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2bhvfqhvs.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2gterpnpo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2vvfggdyt.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2rzddaect.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2jeyoxcip.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2ebpmmiwm.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2nmwqbqli.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2jhojewzc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2egdnktzm.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2rsigveki.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2mghthyux.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2xpmsyxbr.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2uptxqjvn.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gt2lxraootf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gt2bgpmfosi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtfxhrzi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2cqhxdjkg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2iyjkagxp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2mwzyktza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gt2rolgimmj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfvhllcb.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gt2zqayrfcb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2njrchngw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gt2gxqyoyxu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2nemhhcax.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gt2uxycyixi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gt2kiarusro.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gt2jnemayou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2axifwwqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2pumljeis.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2vtuwpumz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gidapngp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2owhopadk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2camhfibu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gt2fmpvuswz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gt2ezorefte.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xqkfdryj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2bzqdrcfo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gt2yjorhopx.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxmuutec.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aooamvzq.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyjcbtoc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2spkxouqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2fwslkuxd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2absbhetk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gt2oobtqtpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2ndpwzfor.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2wfdybkcd.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2axdpezds.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2ivbqxavx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2jfgtxczt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2petkgaqz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gt2ucwxarpw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2mzjsgxdg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2bcgzihpx.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2oizmivtg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2cggrptkj.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2ypkwtopt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvkaigwi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2talivlct.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2niekqlnb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2taimitag.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewvmdioj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrkgvxug.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2ubeppfui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2gunyaxjj.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2emkbqcdy.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2ddygitlh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2krglhonx.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2twkllvnc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2djaldcba.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gt2izrggeou.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gt2omsmhtmu.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2zlwguull.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grcnkdbw.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gt2bahrjvla.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2pvwbncbv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gt2jicahkbz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gt2jvrexdpj.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gt2yphgphdm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2brroegmy.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gt2tugvdjmu.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2dztswcbo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2ezhlfphg.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2urbzpyqw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gt2llbubdxb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2ovezbtmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2syvokrkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2qodcfndw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2taojpmuq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2xqiyessz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2nsyevyth.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2ohnfepof.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gt2haazdsim.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gt2quxfyghj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huqewxzc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2qpznslag.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2oqhvidry.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2uzwmobsn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gt2bpdvadou.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2smkafxbc.html


<!-- 参考信息 -->