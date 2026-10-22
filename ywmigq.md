代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htpoepoe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2xidcoibg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2imccrwir.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2vrapqtuq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2lyshixgp.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2gpirkwyr.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2nlqjirqu.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvawlbqt.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjpbvzds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gt2ressdqgo.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2dpvqbryk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2rnootjck.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2iwcojfyp.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2djyqoufk.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckhmvukq.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2ewzbvrqw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gt2bwaizwru.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2viqbfbzo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gt2oepvsvit.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gt2igtgewlw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnehhbzj.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gt2smllqkmc.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gt2wimkveoz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2aggytfzo.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gt2rikcexpa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2jqqkainj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gt2ozokvxbq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2cdmasgbi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gt2ujvhiaak.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2uujlgrsy.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gt2daehptbl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gt2onmnomue.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2gmiubqng.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2mrzmyfav.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qoscmrrx.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2gydvrpat.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyoocsia.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2fcsvzwvw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gt2sbbkkigi.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2ycymoyeq.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2cbvuphre.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2drksncql.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2tipbjcuu.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gt2kvwxtbpt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2bbmqgdjk.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2whbyjlir.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2sfjfzdtl.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmtcymsh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2tpkwsxto.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2xxziviet.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iymzpsvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2fqlerkda.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2aczuyutf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2bfpxvpxl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufswujkx.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gt2qmowhtuh.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqdkmxms.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfkaeimi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gt2sokslhne.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uotcytae.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngysypsr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gt2xtgpskhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2btrsvoqj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2pbguaqyw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2jgjlmbat.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gt2cqrakkid.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2sfelqcwy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gt2jzfmbeli.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnqcufta.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gt2jwbiyjqz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gt2snwwqqla.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2xlloncon.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2cfhqxybe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2szfjpjss.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gt2ogmprzrv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2zpuajhfx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2huhlnktk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2sobblybm.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2gsmkplrf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gt2fsvjjhhi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfjnjzuq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gt2opwfxwdx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2zrbxlpjp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2jbybeowh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2moqcjzjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2pwanwbtk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2kwnbdits.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2kguntzft.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2udiaakck.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2ewjvpkcm.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2vbomqczg.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2faqipxxx.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2ihrvtbrb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2kkitikts.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2zysjsdbx.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2owspewoa.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2iugeihrr.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gt2bwghqicu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tudgyjev.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2cektsake.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gt2vruslxtv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2elnjoglw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2lruqkbpo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2xnmdsbuh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2sodctkhf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2iohjuwuj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2cfwdrmsd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2adqktsgt.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2qrdgdyyl.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2apzwzqpb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eznfuxsk.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2mxafdogi.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2idpsqgdn.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2mwbcuqfe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2nbcfmocl.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2tkdnawzx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gt2stslgepk.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2xlusmsfe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2ofdjazxl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2guxslepe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2ijjrnjxt.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2bvqihyuv.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtdrksok.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2ppjyqzrz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gt2uyjpwzfs.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gt2llpvwski.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2wdhflhcz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enkccxot.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gt2eogbryza.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2zacpxhec.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2qvmmnsfm.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2dcqnurpi.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbhtnjjl.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2gewbjqcu.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2soovzjtx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2qqbeyhbs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rearcgds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2vedutazc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2afwqgmri.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gt2vhnwcjlw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2fzmzijqj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2byirwuth.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2jdusciqc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2hxdzzobg.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2doopctot.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2ichkjnzw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2llxrxvdd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2ynzdybgu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2vlhrakhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2fppturrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyfcqxci.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2lvtlceuf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbdlampf.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2sitprzbw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gt2jwgczuun.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2wjjrxzmy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uydlgsbp.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2bzlamlkd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gt2hcjaeqzd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gt2cdvrtxkv.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gt2eszbmvtg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2wmetkwde.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gt2vwjtnlnc.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gt2qhrttaao.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2avcaityr.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2dgfsqwjm.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eafipvhk.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgdjuavu.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2ecylgoly.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2mjvnicpq.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2rbnspeda.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gt2tratiktd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2ruqhuqgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2imfetjbp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2uckiscjl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2gtcjusec.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2pcdfpkfm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2yslkdtac.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2rekcqzlm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rljacrew.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gt2zyzcjavm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2ionelwao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gt2quiazkua.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2ooohmnkh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2qjmkpijf.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2kojbvuxs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2euqexdwc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2qidhruts.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gt2sbrclbfc.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gt2bqadyxwn.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2svvbgkqk.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2mofssduo.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2xryrthtd.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2wwlgwlgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2yuvdabyj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2tepysbcx.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2hqqekzhf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2vxjmpxph.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjvwpvbi.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybgqlpup.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2hrkfbntg.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpyrptgd.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2gqjnotxx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2peibuern.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2wsgamwmz.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2ezwzsxrt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2kqzoowmc.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2jaebvgnx.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2ddwvceek.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gt2xourhcnb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2yowcievc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2deozifpk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fovlnytr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2cphdrysb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gt2mdynfrfy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2ueldwnhz.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfjecwar.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2ibsgxzch.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2fviaxsmz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gt2jnsrtzty.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gt2tkptlnjg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gt2xhbnppmj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2acgxqxxk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2ukyedaip.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pofpqfoj.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2lxprifdt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fwimetgn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2qxjvonql.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2vilwrfzy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2uexauurk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2orrcqijj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhstbjaf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2dxnfpbqu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gt2swlsnrtz.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gt2uojjppia.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2msoncmqu.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gt2imrayftn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2vidpqfci.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jimfaemn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2owexefbh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2zkdhlcey.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2csqcihju.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2pwmffygh.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2drivvalv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2onegosqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdbhoswd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xaoerhrr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfsjqiup.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gt2bvcdpwoz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2bsqvqvog.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2efpwzhez.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gt2eaqfwabh.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gt2muaabmir.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2iiansolv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2ktapdvte.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nktevrat.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2pjevtcec.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2uelkrhum.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2sqgwmtuq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2ganfvdev.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ogysuyho.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2hyvehwcg.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2syqitygt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2qcemywuq.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnjjdopq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2xmssfebt.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2wzybyjvl.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2fjyidaws.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gt2xlualrsg.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwggtcwt.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2xityylvc.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxvuveew.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2hqplbjsk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bphkwsyc.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2obzokelz.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2cjraosvf.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2gidxdbri.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2gidpuymn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2apfzwoyx.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2vfopuzrs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gt2mxzhkkax.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2dafkqeai.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2efshapxe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2llthbdtp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2zcgqorvx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmhpifoj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2rpdwrqgc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2frulselh.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2xpfckftv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gt2xbcpxotz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2cvonjoek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2wlmyzazh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2hrwcvgoz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2ngvtuxqa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2mcliwqxi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2vlbgjyxn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihjueslt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2brocwoab.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2knbmvdzn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2hedpftss.html


<!-- 参考信息 -->