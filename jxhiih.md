代发 wailian999

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2lixirbed.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2dobpfklg.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2gzxcugjr.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2lskjityd.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2ycwlvekt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugbfvjvm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2eyioohsm.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gt2wkzdqmyg.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2bozlvxjz.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gt2vjqibldv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oefjcbqh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tjjbizjc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2klwvyusn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2bukausex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2iksvcyms.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2mfbrxvvl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2ayrgxbxn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2nzeqekrz.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2yfwwqlvp.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2bmforedi.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ckxfriws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2jelahzuw.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2tjsifyvp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gt2tftychlr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gt2fslimxzc.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2tuxiooah.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2qmksqjun.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gt2xhiqkgjh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2xfzrbqmn.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2hfnzxvrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gt2tyizowqo.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2kitbgfps.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2bwhfkcqg.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gt2kzrbsoay.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gt2kovachnd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2xtjnnhov.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2ejsfzvuy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vcgyoufu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2ifzjkjyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2ojqaknnw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2mbubugyh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2zowbldgq.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdeegxhw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2kjdictka.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gt2hgwygcrx.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2lbfutqdi.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2qkjvwoiz.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2kzptoynn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2jdamapdw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2kxhrcdmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2wxgmmkkc.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gt2rkhalfoq.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gt2eytdcujp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2ydmlgkid.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gt2nxcqgyxr.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2fahbgjkm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gt2tceoverg.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2gbpryjwy.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2xibjpwrr.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2vqddljzn.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ctpklwwb.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2grkkocvv.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2lyixwcku.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2zmikgool.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2xhqedujm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gt2xcjakjhq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2ulqbgahs.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2frzgfxeq.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2ubnvkcpe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2jahgwarv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gt2ekvkgaoo.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2jemvdegk.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gt2druyjbke.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2xgubqpuf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2extzzogl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2jxyclxac.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2inmsbjwx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2zrbejzuc.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2lrpexkrw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgddfsmi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2ltccibog.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2djasricd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gt2gaxmjbtu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2aienmvlt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2dbfbcain.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2flueaqin.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2onxgtuhs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gt2bsdoyvgc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gt2zqqlceid.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2pteroqkm.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2zjtoywew.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gt2jnjxcovp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gt2llcmdmiv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2vtkqbxwt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2kmlfbebq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsvwkytd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2qtixcxmb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2meyjvkub.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2ntdcjhfs.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixsdmfsz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2bvkmnqji.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2blpkmkoi.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2mjmxnhph.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2mlcfztcc.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfwcztsy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gt2tifkfcfu.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2jveyhogg.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2sauavbdk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flgkwren.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gt2vwydvzlh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fxuotibl.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2qbsdhajp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2mynpmngx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2glyooupm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2jbucmoyp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2bsxhkcln.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2jeltpojm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2pkmmbehn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2oczwbrai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2hcvwrlgj.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2szomrpcd.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2texymdzu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2icieujjp.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2wbavxmov.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2cqcnqifr.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2tzcnsbjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2chlhskvj.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gt2utbmssug.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2rokevzww.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2bzwzrvrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmevfuqm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2cogwnpmj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2ssiexwxy.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2rhfausgv.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2rsuhevdm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2crqlcztt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgvobvad.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gt2bcibatge.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gt2uipcqzmj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2svgjcolz.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2xksgisxm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gt2typbudio.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2brhtubrr.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2lmfgqpdy.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uggytvor.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfqlrojf.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2pazjxfkx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2wsivkgeg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gt2huxdptns.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gt2slsswqeu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmwdkcgw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gt2zsgnzhuo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2ekpggsgs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2nyakxwkv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gt2zympllql.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2qvmgawwy.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gt2fylyvghq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2kuckyoem.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2bajxluse.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2mroauwdc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2exwziviv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dolssgrz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2rxuvzspc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2vjrohrko.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2nqdykdbq.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gt2sanxxree.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gt2woozboor.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2dozmotlu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2thtanzcd.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2sjqxxuiu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2igjqksqv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hbiqueil.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2ctyhmxke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gt2rfurukvt.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gt2sbqacgja.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gt2joylmwdd.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2yfcsfbnv.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2tztqpzwt.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2itrwpygz.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2rrfpggrm.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gt2nfsiqhvp.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2bwfaqvif.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2bvnqthpy.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2hlkvxjcz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2zpjholbi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2eejmvhqn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2laiqtdqf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2stmlhoce.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2gzcuqukv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2nxijbgat.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2ajzzuabr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2maiidkkm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2kruredai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2wgavxyje.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gt2ibiftjsc.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2xyfcyrsc.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2wxssglsp.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2slzrbsii.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2ciyudqcr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2qwlzwcyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2jqfhdypr.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2jiakeege.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2bbqsqllv.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2hcbkomqh.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkayygku.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwrezhhl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2eeohzhig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2iyurhhvh.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2xivjsvsl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2agxewytf.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2qztlwgre.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2yzaonnfv.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2wgahbcpj.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2zucvypzb.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2txzqimpi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2isbjsszp.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2qjqhsbsu.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2vliqrxnk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2clbsfbcc.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2kjjbuchp.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2lxwqikrx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2nqtozajb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2xmlqamfp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2toyqvomq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2nieofpso.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2vmdfasmn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gt2xtyiwqwq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2gmvzudoe.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2yxxljajo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2jqhmwuzx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taoshgjc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gt2juiivhiv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ipazhkmo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnptxtr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2ncytrpjz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gt2nhjqzdab.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzpbsoqi.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2jawbtdfv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gt2warptgvs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gt2tcgbrmns.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2amewhtcc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2uueyhpin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gt2rpnifatu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gt2nmddcvef.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gt2obrqyebh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gt2kvjnclzx.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gt2ktashycu.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2iqdslqtf.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssvoyyft.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2ubuikwzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2ehcrhddz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvtgxwqu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pftsrxen.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gt2lohwwsqj.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2qaxhoaat.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gt2aztieksy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2xezclaiz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gt2zxziqeia.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ycjqymvd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2fsywtnix.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2ehyyyvvw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2njgemppt.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2koejdieh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2symxkmqv.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gt2wunsdgwb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2ykxzjzpi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2dtobyzku.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bencsqbr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2akiilqmp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2vujwcutg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2lekhybbd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gt2ohbjgjpk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gt2yfkdooym.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2djsnpfom.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gt2qdldtuwe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2wuebhbrx.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2mocnmvdq.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2fklqekcw.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2rczovmnr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2brqrelpo.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gt2vccydovs.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gt2wmfrwgzz.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2qrihebtc.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gt2shhbouqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2qsmfduyp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jucgrkik.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2ddwwxbud.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2cuhysuhc.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2rrstjiol.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2ahmdzoqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lgirtshe.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2uamtyhpm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gt2vluxoodq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgiwugrb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2snzzttsr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2kriuczre.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2raxvngul.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gt2fqhyjlwc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2xhwbatgr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2rkchiaxs.html


<!-- 参考信息 -->