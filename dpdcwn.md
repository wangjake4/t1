代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtuzlvrsel.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtkmzealys.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvdrfpzm.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtxlsuwtcy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtknaxbozk.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtunyoayyp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtergchvgo.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtwujmpuec.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtglovitnd.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtkpuhsakr.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtbxweulpx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtasarncby.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtoytwmgdc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgzlunhtl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlamqycni.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtermkwhcr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtukgswmmq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtzdmecuid.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtdsgpvhel.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gtnjzlqxjv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gthtokzxzj.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gteuphxbaf.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtywwzrkkx.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtzqcbvigk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtpohrxibf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtaupenkvq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtmsmpmqjf.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtczxenvhk.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtntolwltu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtcrpjduya.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtqxolfqlt.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gtgpoftzrc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtrsshgflq.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gteoowxgos.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtskmvqgep.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtjjbyopzk.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtqfowlfee.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtwhwecxjv.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlveytmjw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtpowvjhvi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gttwlhcinu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtgqubnmin.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtxsqbscwb.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gthpprqtyg.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtkgnoqqey.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtigvlrfvz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtmmxvdrhn.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtufnzcfrg.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtxnkrjboh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtryxgcano.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtruwqllrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtbywtdzgr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtdlqvoaug.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtczukzrpo.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtsjjecfac.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gttamjsejy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gttufrvrrv.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtkxmmolez.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtqvkzzoaz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtmzaubjts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtfvvfmfas.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtyhojlaaw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gttsucgowk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtkcixvdtf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtidhmrfqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtsutstpxn.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gthepdighl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtboocrnhe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzayypls.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtxshdwfmn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gtnfcxdrim.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gtfrxhfwaa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtnqgjtdkc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtnjuqysrv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gtkcrduvih.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtzlgubbtl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtdxxnxzcq.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtgqnxdhnp.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtgunlgsji.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtjhesqwuo.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtzwvcjcrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkylzsxpx.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtbnprgssv.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtwvqcphgy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfcuqhpfl.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtuicqepos.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbcryimsz.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtqjopzwpf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtehqmgdjs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtrnwpconz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtpjuqpfcl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtcvvmwghw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtjtjhwrzm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtqptpdvak.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtlfmuzclt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtcbejjamy.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtadcembyh.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtgsqntgis.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtqyimgpnz.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtedqzgdss.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtddxcyvjl.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtezcarnqz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtefzlkxmb.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtjqukqatw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtnxxgvpdv.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtmicwtxmq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtjvpxkvng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtxmyyextk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtqbieaqva.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtkeoxvoql.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtsvzwyszt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbbzowfs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtkursxyrn.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtdoobybgf.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gttmrvjirx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtxoowatof.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtfwakiyhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqolwhvmh.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtltraebab.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtirhghbyp.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gthlfhgkue.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtqhhgiczb.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtqmvgsano.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtyzkckhke.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtxsbqsvtu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtxyrylesm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtdfrbdqyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtenkotsuy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptxeicnv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgqkkecg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtbjcludfp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtorvyllom.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtqkmbvtwu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtaxszmmwt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtgfmrysfa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepvrjvvp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtotjtxpaz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtruuonxqq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtpxmgptks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtlfcwbeao.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtqalxzksc.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtqnokunsl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gthckmkvsl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtxoyfcyik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gthslzxqde.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtulxxsobk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtudnzqiaz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtxgeshkrn.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtlqgjwpmu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtbvqbtdex.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuugyexc.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtqeemjvcv.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gtsfqkwtei.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtldkjtpvr.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgdulffp.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtbzjhzxoa.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtepqyobyr.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtcdzrxpdh.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtswuqlerf.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtwubrbspl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtobzmukgm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjvtbqedk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtotbsltio.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtwwkstytw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtdauhhhuw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtpmkymvyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtyrigbtai.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtztdmjvar.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtdjcnbpvg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtvbmrtclr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtgezaukve.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtfnyijmgd.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtsjeaofdp.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtgrqdsdry.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtapfhmilf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtmlktcbil.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gturcgkkti.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtjhmwfqkq.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtjlifsuxv.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gthjjhlonl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrraiqqhd.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtxgshsocc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtndhykrcf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtjfqgoqoi.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtupyoanlk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtnsaxwxyd.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtllozcdiq.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtmmuhuodp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtglprrojk.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtzxtwakmb.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtkocbtsyu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtjlgpdwij.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtxibmveeo.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtelrwiepo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gttdeywtlb.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtkhaggcxs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtshoukvur.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpkgqgq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtjxfljoqw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtzhrgoicn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtgdtoiebz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtwhghayhr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtcxcmgwxr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtltmofejq.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtsmiydupd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtnzlhevdg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtouyackbo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtoaxprldl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtelcobrrf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbhyfblm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjxorkjt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtoewpqeew.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtsyqjvptm.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtcdbgqlwn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtjopmrjzm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzwdxyjeu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtqfuaijzd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtogblcsfa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtrkuwoydx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirpfeeju.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtgqoxxtan.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gtooemiadc.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphdxbqka.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtawyimaxy.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtxdeffhsu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtvalqqkyi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtqwgmcdrx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gthwblgfyb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtjzhnulpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtdmalrxnb.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtwiawnkmp.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gthtojcvzm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtvgbkrmfs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtkrdyigyw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsyvcdzyg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtcxxqwyxa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtsugcqmfd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gttetqvjid.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzozwatg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtctkkbfni.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtoqrqypdm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtuvsrzoek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtxcifcgnh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtphabvtir.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gttnndmbhq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtqexwkxdo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtjrnkcyrk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqymdmcfl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtwdpjuyvi.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtogljxoqi.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtgbfgtuvw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gteldglsuy.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtpaaledqg.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gttfnefats.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtztfcvyns.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunqpvege.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtjuaxtgoo.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtrimjtidx.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtcousnlgl.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtznrcpvza.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtamvucwlf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtfhojchrh.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrombrdsu.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtjfwgepey.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtdpuwssgx.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtwlyvjuyr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtklyjcopa.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gttvexrkmy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gthjbfdorw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtfoecpnux.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtzgfsmnmn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtpgvjzrvr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtqpwuhtxd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gttbhekjyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtlcgilmnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtprglhqwm.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gttgwbdose.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtfwbqujhw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtjmprnoty.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gthxjywitk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gteaawstee.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtrutoekdu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtfsmawcig.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtpmsaaqyh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gthedazuqb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtghgntnwn.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtozrpntcc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnrxpbesv.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtyosqiadk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtagggebgs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzceodkhm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtsbvrbgxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtnhfmmalt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gthmnqvknc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtamzgcbjb.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzoqogfcd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtvjvzmvtr.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtutsihonn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtyjeenftp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtuwodhmyr.html


<!-- 参考信息 -->