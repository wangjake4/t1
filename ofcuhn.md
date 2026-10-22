代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2krerijej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gt2iaqgteen.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2tdkgyjcr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2forrsmhc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2kddjnjvu.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2ldmtpyhc.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2xdihpwwj.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2xegghsvg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2eqaipvrx.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gt2lezbotry.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gt2qnabbppm.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdguyucw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2kqkkbqmd.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2ypwouegn.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiiwgyhk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2sazkhoeu.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2krevfutf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ydnpatlw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2auxyuyuh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gt2zxjkhnkf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2cbuezpnr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2assecnrw.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gt2vssqetdm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2rsbxlmbd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gt2geuhftwn.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2pgivbybr.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2wfemqjxe.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gt2zziefdev.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gt2xtyzmlhp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2zstkpazh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gt2bemzxwyw.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gt2ajjuixxi.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gt2toqbjhsj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2dxxozhql.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2glmiizok.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oraqvdzy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gt2dcozsxrl.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2ytumgive.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2lzpjzipq.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2spazsdtg.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2ksxxkbgz.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2hvusptnn.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2wwnxwsoa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqxtlqeq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ugniztot.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzdrdrvk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gt2khlptigv.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gt2bcrffouz.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2pnqfdzph.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2uuxzxsml.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2yfodafmy.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2oatylfbp.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfvqlovb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2vxhnbnvv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2xjhbpgcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2nynyjcol.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2fortzzwq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2dqsivpfr.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2kabvwxkv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgyaripr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlqsmjbq.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2lpwppsic.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2urepnyfh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzkfgzmt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2etbteppp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2hhzylpaj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gt2zixbnawv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2pzwotmev.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2xhcnisac.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gt2etfwaorb.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2iifolemp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gt2nezfbuzu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gt2wbbscacm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2afvlyqfi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khvvsvzp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2iebuauun.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2eeewefkw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gt2dbpdahiu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2wbmpyybi.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gt2extiywou.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2ibztbvbp.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2zrlvjqwt.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzslggqn.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2oohznkwv.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2alennsrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugvfmcxi.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2jtgsigwn.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2cezlppoe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tgjlhhdt.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2duknpmqj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2oovgzkzn.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2hacnlvjr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2idlcgfed.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gt2zrhcaemu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2fqoaftmm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2lddjofgb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2glollhoy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2bftzivoz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gt2bwwiwdeq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhfqmore.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gt2efhfvyga.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2zcxlroan.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2tplzypuj.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2mivhhhzo.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2zqwvgjxt.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2qskliupu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gt2obrjrcqg.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2muyjboyg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2rkgyjqur.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2vjapquip.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gt2ncxuwwqo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2ascuyebf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2vadthygl.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2hcxhnhze.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2niksvjgh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2ghpyqhwh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gt2ygaabsru.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gt2yxnanmlg.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpwfxyra.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2ybccbzse.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2luttnrne.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gt2wbztahnz.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2dhrhejea.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2wnolfjun.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gt2rbdcgjzf.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2ynwzhwog.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2bfojpfsn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gt2yfadggks.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gt2zhlbafoi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gt2evlkolqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2oerqgpoy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yorynrbk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2ftrcytbb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2mvvuiqyw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gt2gjtnocxw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2emmxndfk.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gt2iirddznn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2vjtawntm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2knephccy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2xvzipwvl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2eagqwsup.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2gyxprivr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gt2znvbggpk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbnlyldu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2eqfjfzsk.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmebecvt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gt2qcfirnyw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2bcusbbev.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2nntducov.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2xuzqfrgp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2ljudmvxj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2lymqeatg.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2utrddwlr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2biuhkapq.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2qdzfxfly.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2zqgvxjcf.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gt2hlkgrrwm.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2lnxlkdnc.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2upcasrzj.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2uuwolung.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2cphenunt.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2awofhndg.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2wtxjznpi.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztdsxejl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2npamzxsv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2gjyfwyur.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2gwffmobx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2nvvktocr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2ibwnsiru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gt2bpjzrdpj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2boqgkojn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgknzsgk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2xkvbmhbl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2htkpetjq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2chjvdywc.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2izdbrqyx.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2fqbskgfw.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2wqqrmkiq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2vewimlfm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2gylrlxma.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gt2ytxcfkzg.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2pzxinltl.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojlvrcud.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2pylzrkot.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2hdizihdb.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2gtimnmoa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxowjvnm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nltjulhv.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2shpcfnqb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2xsyvsbot.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gt2gptzmend.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2syvtvcnh.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2kvwxtvps.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2dadidkko.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2yiyodzyq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2ivsyaisl.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2pgvgpcov.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2ecmnhovz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2pflvvnil.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gt2eqoizwop.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcfbkwzi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gt2soaaqxfh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2xdeksbof.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vtgdduyi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xmvsfyta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2jdwqawaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2qvfclyjg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2clmpkdic.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2xvbtgcgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gt2lazakpmi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjqtirwi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2mmsaghjs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2owxmhylr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2qwlookrv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2zaxzicxg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gt2sgqigmuc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2xonsbaca.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2xmecpijw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ofqkjvyp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2yhviepbi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2egnjscwy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2dugaizxp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2dodxendg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2hwbrxsxy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2mdbyqghw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yielpjtw.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2lfvonkam.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gt2zpjbhkmx.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2kkmdtshq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2zjjczdku.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2ndvscqft.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gt2ihdekatf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2gsbntdew.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2lgkvwrfg.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2prxczeug.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufalwvsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2uavfghhm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2qbzuekpd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqykypqx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2czsoxptq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2umfehysx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2nsyhvrqk.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2gwanqctb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2tflxddit.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tubjjvku.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gt2xhtciiqv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gt2vcrcvrld.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2glbpfpof.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2sumdhovn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2iacmqcbv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2bfmkowxd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2smvjbxqu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2afrhdlyr.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gt2ihegumno.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2onudzfvt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2xdmwjtzr.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2rxmtdtdf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2zoojckgp.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2hqaoinal.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2gwqljabk.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gt2pnhqcxwt.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2powdsaqf.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gt2ymapcnjg.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndmcueyd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gt2konosbax.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gt2sllnftdg.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gt2yvyuzitw.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2dqmtskhu.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2iscnkcjp.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ninhpiov.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2corebpmx.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gt2crpyoyzn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2wgposeiw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2kofzlbaq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbnnrylb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2iihhhsjl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2djephzql.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2yxgkthsw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2hjftnlxl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2qlgafssd.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2mougowke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2eggfbohu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2khvtdcjj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkqpdztq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2hhradvjv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2hoevtvzs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2iothkjmo.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2nulzgzyi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2wdnzvyqy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2unagvshr.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2bljlkfkw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2klpyndva.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2brfuvipc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2qwevnogr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2yzdoowxi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2reeiokty.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2omrtlpbh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2fiadsbpf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfzcabwp.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2snjvlsxg.html


<!-- 参考信息 -->