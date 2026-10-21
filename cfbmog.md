代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtcoqwvyvm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtxxsceroi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtucatjdse.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gthiqyttzt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtmjfjreoq.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtnmubcyiw.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtuczspnjv.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtndopbwmx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtxhhoneqy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtayxhivdf.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtvxxpkstr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtjonmfznp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzfafrzt.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtglynbpmv.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtryjlkcdt.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtdjkvanug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtwprchvbj.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtqfregikd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtccjkhjfn.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtyyfwptml.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtsuhfpsbu.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtxqmfqmvo.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtbnuvzfyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtbmllndac.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtauyltdyt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtkvfzovxh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtdnhhrzbu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkpbylee.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtprgyrbqx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtvkairffl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegdgbixr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtlnlkcmjn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtsztnzrsw.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtxlgykjpr.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gthhwtoctv.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtfojdrqog.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtxddpupft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtcfjzucfd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtroccdlij.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtnxjorfxf.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtdzmfguww.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtltddaqxw.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtjqweosmw.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtfpdxitee.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtromtszvt.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvajplolm.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkodnusjt.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtkodxmrel.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtuetqdqff.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrymzbpdt.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtowhtgavc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtsmncgtsr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtsgcxsndl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtegqnofdm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtksatbkaz.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtjorvrlpg.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtxsbyoxhb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtbalxopwz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtgcwowqju.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtirosxjpb.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtpussyshi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtshzjdvyj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtqcapydes.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtmeonooeh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtrzfzaycx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtuvguoihl.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtoiqsizin.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtajvuhhfm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtyfabagme.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtmwgtspsd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtujwkgmdf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtoivrotmf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtidozmwel.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtxpikxubp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtcktzyimp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtthngqvhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtmuuqthfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtrlrskkkk.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtskntxfgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtnwfmcjre.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtspsdygaw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtjgzxdvqf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gttjozbjjy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtkwakkxqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtjfvhxcse.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtxyhhxghj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtuphzrrfb.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtqqhjixgh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gteypehvkf.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtcvtzynei.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtwaqheqjs.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtstkiwxxv.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtpiprmtxc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtzsmzlvdb.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtvumcpack.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtxvmbpsjd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtelqtuvdx.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtevbznnnh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttikuloey.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtwjiftfyk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtczmeuagx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gthdhchoqu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtgzfulytj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtahsnuxgf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtgjnriyzc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtayekxepq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtudzlbubo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gthhrluowz.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtqagevjzl.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtggetbopf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtvxzkvsll.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtxqkqyjfc.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtxwhmruzg.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtsygiirlk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtrpbpdgvt.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcroebhya.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtegvsswip.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtfkxuxtrq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtfromllao.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtqbsqeqmm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtwnjbkiod.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gteduoradz.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtdcsiwpts.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtmiwapbvk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtpwluhrze.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtuftvahgh.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtydnnblwe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtdmdiioaw.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gthocaujyo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtflbqsfgv.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtlxrbtuud.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtmqsznoxd.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gttudrckme.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gteffmqodc.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtelxnfqhy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtvklpjjcp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtutmafhhs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtxkevauui.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtijkyhhfd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtaamsknvm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtjqxkvwtc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtjeqkeuhx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjlzygyw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtnasbzpuu.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtflcizown.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtrbjbbblc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtwbiaeycj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbxzmecvv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtikwugean.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtafwqizxv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtfalbbwkg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtyrayvybb.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtkckoywgh.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtjnslziho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtbpjdksvv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtjhhcauwf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtuyioyrxo.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtywyctlap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlibozbar.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtupdlnpcv.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtequdkrko.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtuzjrffod.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gtlencmnjm.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtwdhvxmdt.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtgpztclkl.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gthavkqfzq.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gthpycakvf.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtizhxcwbn.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtrpdskzsc.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtxtswwued.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtkmblbcno.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtfyaoydzv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gthmefpkwp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlltsawuw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtjjlglbzt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gticugzowp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gttzuyrecw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtmwgmbhxh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtfeafluhe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvgckkmo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtycfjylfz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtosinvjkr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtifjgwmys.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinyyiubu.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtqjmptgfc.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtugilfptf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtagpnwmrf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtsqzsdqpt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtxaaklknk.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gttgckzorj.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtrmoesmxc.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtjzafxtol.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtlvyeszln.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtehvejqix.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtzagzubei.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gthgkqtkhk.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtwgobsfhs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtysjnjola.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtbfvepnuk.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtjetbqrkv.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtauahtjnt.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtikrjimdv.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtjfbkifiq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtllqlphdk.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gthmjsgfwi.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtwnwfktng.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtkqxrdoyz.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtywperyim.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtqexxyuhz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gtcvsqvmsr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtujgesyxe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzkyhvrpe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtfismhioq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtxslwqkxm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrmwrzgf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gthsroaode.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gtntkzsuea.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtcyifxxpd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtxzqixrhl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtjnxhxzpb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaoagrfbp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gttnjckqug.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtygouokbn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtqvrckgqr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtwjtpzpzr.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gthptcsfez.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtfovntxyw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtkuqldbgj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gtqskgweig.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtkzliqjqn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddbmvzkz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtcmleqcus.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtffnjjpes.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtvkajxoxe.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtfchkifla.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtcbwpwutk.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtgoytjvge.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtcgeuukyp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtdqidimey.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtvogslegh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtprbqeypx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtfyvzkche.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtnljmyqeg.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtoivqxnkx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gttawypfww.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtwkecptin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtgzcwjtru.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtjqthylqp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtiuncwwgz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtqvfhdxix.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtrxqtffnw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtgdcejyax.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtfmyzwpge.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtslqslnld.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtarrsezvm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtoqubagqr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gthmweuxmg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtbrkzzlmn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtheadkarl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gtnmxwhoim.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gttpdqlhvs.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtrhrlcgpb.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtjxbxrkgl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtohndrjzk.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtieqohmtd.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtxmmmqufw.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtkmxzznlo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtqjfwqhsi.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtxaxqvspx.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtoqwbxpnk.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtoqxvpqme.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtrnadmmlj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtbukpfzzq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtngpelfjb.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtovtliqzb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtbufsiqal.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtnziewarx.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gticupurlg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtoxkgrehy.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtrntnfsyf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtttrbxywl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtgpirbpxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gthcprhigy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtldgwvgfi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtnthlcksg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtcpickjss.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtprfkkzft.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtnjgecbbc.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamxgczjj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtydftgqwg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtbfzwwpgz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtnrdyelpw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtwzkkymzo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtfwdenlqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrmhrewv.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcbgwueq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtwswipcvb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmjsqqnyj.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtbtorevjk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwpdnblue.html


<!-- 参考信息 -->