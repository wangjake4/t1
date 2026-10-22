代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2riwwskvt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcdkymmk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gt2dheovwvp.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2nkcktknp.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2apwwxrvl.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2deqsdxim.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwjcyvmj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2tlkavpyz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2yyhavpwq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2zrqwtuyx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2hzukrnls.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gt2mdumurro.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2rtzpbyss.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2cogivxid.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gt2cuhbregv.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2gdfcepuv.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2hugrciok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlnatswq.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wecvgpcp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2bgznrdbf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2xpcanouo.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2qippqurc.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gt2ugzkumbw.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2fvannfoa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2dxlsytuz.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gt2ukdlezhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2jjawvebu.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2yhbqzsdq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2xmlhswuj.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2eowuqemu.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2yvydojyv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2adjimhhw.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwjqtzkb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2bswyekdq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gt2arwgrqhs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2huiuojfj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2nwdnidqq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2ndmvpagu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gt2ogaceecv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gt2chlucdht.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2jcdoizzg.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqyxxpyp.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2bqfwxfxe.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2wryylibh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfhbauuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2jfaziywa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2pkmunuca.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2nnwxppzz.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2osvapntx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2mjolshbt.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2dwfurjum.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2ickocrlf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2gxwgfxwt.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2amjptjxe.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2jwzjnmas.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2upvlebxn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2nvrmwvec.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2wfihzfrq.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2tgsyvlya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gt2joilwkyr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmiclzxf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gt2qyhedzik.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2yysuiyru.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gt2waixfgxn.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecdteoap.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gt2kyolideb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2ilfegptg.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2eiqzkjzs.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2yyrvcmjs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2xnkrclma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2godrxihs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2boxuhpkv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2fzvxisob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2hatacfyf.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2ufgtbydn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gt2sperquoe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2dassgmpq.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2frexwbys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2vafgdwyo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gt2mvufjrab.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gt2cpcinkdm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2tsfgxxwy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2xieehqcc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjzayzjj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2ghrwnbdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2agxenujx.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2votbppqn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gt2oofprgoz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzfkchnr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2qhmzzrol.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gt2goqmitnv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2catwgpyq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2afbwgbwm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2okldaine.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2rmqrsjfy.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2qbkmkskf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxptounf.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clgtppcz.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxcjoidh.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2vhwkdtub.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jklslqjt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gt2akqndvej.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2azmnelys.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2uafjlmpe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zjqmvilf.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2dmxfrdif.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hycdfkqf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzsmmgt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryyhjdnl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2tczhwfvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeuuioqz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2bwpvkiqt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gt2zzmlgbtz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2ecmzujpi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gt2dahmrxqw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2gloxwbes.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzbbhzsb.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2mirbkykz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gt2qsxijsdf.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2yehalrtw.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywbpjlfn.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2jlmjuqqk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gt2uigahesg.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2lqkealpt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2xpezelkv.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2bhsajofc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xivypraa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2pqygfhhh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2juxebefb.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qucpizna.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2nhfsycqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncqwxlik.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtthpylp.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gt2qalrggbn.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gt2jwpzyrwn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2gpjcyzdn.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gt2jekppdez.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omldqhjk.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2orzgdjkn.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2illefyyy.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2larsfuwa.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nofprirw.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2owvgbele.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2enndttof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gt2hwugbcne.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2wvthnrjh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2grdkoujy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gt2qjziucwn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2fwoyzbtt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2svcubkvu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gt2zertzvej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2ijkpeiaf.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gt2sgfcqtfs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2gdlnpmxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gt2ughmwwzn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2owvwzxnx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2rjyzxlru.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2vhvcrgjg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2hadasrtg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2mfqqzynq.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2jirajvhq.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2hkpztulu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahtjrunb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2qelzofwg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2yiqbdxxq.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gt2oylmrqom.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gt2axiijtwe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2ykigvupm.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gt2izgjpsgv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gt2izmstfju.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2kkcqduyo.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgucwhnz.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gt2lbewoldl.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2fyhkwglu.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2gifwgxrp.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2gslyjedc.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2djfgvdjv.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2fjrwciow.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2ixcnayab.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2coaynypd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gt2kdckpagk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2qqeiihia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2wqpzywcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2nnvdaueo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gt2yduwlcon.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2osnrztch.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gt2awamkrlq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2rwlgwtph.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2hvaicatr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcqsmcai.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2xjphdajk.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2fdewizso.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2vgaxboop.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2oflbwsxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2whqgqrtz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2rhnnyakb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2pxahigwe.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2oabvevoa.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2eefiupex.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2jpszfanj.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2mybcjdhs.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2pzsryght.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvwdyqjn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2tuyzgofe.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2esebmwyv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2bwvjlguu.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2fznffawh.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2svcbfxbg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gt2lbhlrrrp.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2fznbueyh.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2mhznuijr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2hfbnnoyg.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2xnixphxy.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdxggshf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggfrkimu.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gt2ykvfidel.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gt2ppgwirpi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2uxfqzzxp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2otjglpla.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2evjcspsa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jlxxepvv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gt2wuexshob.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2quvihzpr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2pgrrlgfb.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2qidlhpnr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2ycopinqe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ecrgrtlz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2deaahmru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gt2scntxeng.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2jeduiaud.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gt2yufjstlc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlgkrtq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmubaylv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gt2kmavmryz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2jdsiwjna.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gt2fzxtffuk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ptgfjrrc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2fvmpbgdf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gt2rtaqrhsy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ryvqowgp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gt2pnfsqftg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2omosdtmy.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2demiqdmk.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gt2hubxgkbl.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2upfmpluz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2txcslydy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2avlzxkft.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2xfbvulxh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gt2cgjqovad.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gt2djitwfeb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2mrxhglxn.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2duxcsshb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsevsthx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gt2bzurewnt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2upfchhrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2tdujqxob.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ihbveveu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2kolpqwkx.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2bjbjivwq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2zbdwwlpk.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnuxeazu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2esfzfhbm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2drxntwcg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2snaaeivf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2ynxqzyea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2yriinnkm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilrxebsh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2iafmwgnd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qttrjkih.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2njgsdskt.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gt2hjwmmsal.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2lndnuzsb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2uowhcfnl.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2vswefdlh.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gt2fiafljmc.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2ccydoxbn.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2swrsrpgf.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gt2masovkwa.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpxxjrgg.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2liuktmgc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2ngmzdplu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fgmllvjr.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gt2kwegqpck.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2bbvonoaq.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gt2sfoxjohw.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhdmkpyw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vjwpibak.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2jwuqdihy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gt2bhakxnmv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2fjbnvqul.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2rbvnvrtj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2wobzdagw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2iyraysxs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlywleht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2olzbwyjg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2latxjxct.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2ezxrvnwo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdqhyosh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2yotatyfu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2qckykuin.html


<!-- 参考信息 -->