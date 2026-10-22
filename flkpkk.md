代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2wmajbdjt.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvwgueha.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2ufawtuqb.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2iuaejbdx.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2kfecbzwe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gt2jrtymwlw.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gt2wvlotdgx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2apueutvp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2anoknhsk.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gt2eqyfxvkk.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2lljlarud.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2sycyvbui.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2jvdfbcvd.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gt2rcfhggce.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlcykees.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gt2tpqttnqy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gt2nqpyyyqc.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gt2mohuobtj.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2zwldmvti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osxxeeju.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2lrddzuiz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2flmyagun.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gt2qmuvpwyn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2tzctuzkf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2frukgkmt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2tpyppowr.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gt2nfeqozob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2nqmvqwhm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2nkyqiuov.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2djvdemfs.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gt2wrbzxkzz.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2azeissye.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpjunezw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2ogpmbgmq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2iheswpjq.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gt2cfbxirwr.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2djphlorn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2wklrdncg.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gt2znjxeyit.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2dcznpnsv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2ykudlhcq.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2pomwfrxz.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2lrwvcvnb.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vglpiypu.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2eqazkhoc.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gzsulgyu.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2krjlhyti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2gpbxvsey.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2gzuizbcc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2lodqbyhg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2xksrklop.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gt2isovjbbx.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsduykfd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2ctbfiuib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2iurobqml.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2iqbepgim.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gt2idwvlwnr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2gykltvbx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2drnxruqo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkjwicwk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2rcdoopuo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2ftiugzvy.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2eqoftbmh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2pnzstsuj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2icdidhir.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2raudswmh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gt2phlyvsae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2djvxhitc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ghzoszep.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2ozwmhzar.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2xyrpzdsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2ppwyxsfs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2ktddapgh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2bilzhvml.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2upfgzddf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcnwtlfj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2dupyrzpp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2nyibqlli.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ximtfzcw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2yqlrxhzj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gt2jjwdtukq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gt2gqfgelkb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2tffneydg.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ulwfrahf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gt2cvlqckui.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2ezsnpgar.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2hceobvpl.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2toecfvzo.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuehkhst.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2mcvrntnx.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2inizaspd.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2lrnjpmqh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2daonlblr.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2loeveafy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2bgyfokhk.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2kipovgcv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gt2ajukydkd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2ppwridav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiwvzhea.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2vzejnbxu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2ysnmgauv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2mdqhkybp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2skysinta.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2fvgsfhgh.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2orbbxihw.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2gccyhwod.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2xzqbjtuc.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2fklmoqqd.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2kbgulply.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2omijmncd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2rgqfddsr.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2tgrsmrha.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2wfcfdkeg.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2vsrfedaj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2behjrsnu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2exfbwxlx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2jazhnqwn.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2syqkrave.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2zmacnjax.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2bqiatvlu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2aifydlgn.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2yzpjzpvy.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gt2yfmhubhw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2gnotqing.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2xcgilywm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puzsdiqz.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2gghccrgp.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2fqqqbche.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gt2kqmhlmux.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czxpxxyi.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2vuovvbik.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gt2tntpyomv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mehqwbjm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2oqoybjix.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2yxxymwmv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gt2blldzewt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2ztzmmzvv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gt2oodhugew.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2aakbkulw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2hwezqqet.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2hinefbqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2klmukzkg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2rlnxvuwz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2lvtnuzyf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2axaqrkqa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2xafygkqo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2iqlucdsy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2hbmhmmpt.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2kkzcbbdq.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2jozoepoc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gt2xbrfipwa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2obebehhe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2qaoitofd.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdqayxay.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gt2xbneayje.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2olpknxeq.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gt2jjrvfyfc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2iadwofkj.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gt2mvcbnmad.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gt2sbjcalvk.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2fxmuunpf.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2cdvflgmz.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2wxpscgmp.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2advotofd.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gt2xsneivje.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2lvvrwolp.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2thzokvwb.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2nihehaof.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gt2mgfpbjmj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2dybwubal.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2rfqukbds.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2boaczbgo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2lodpcgqe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2pbqmglbe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2hcvocqgf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2iremsami.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gt2jcuicwza.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2mpmshahj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwxlbceu.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2pawprtly.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2yexuttgy.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2meydihei.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2uvqmxzvt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2mnvbomkk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gt2vsyyfqzd.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2zanqlihb.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2sakdtysi.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2rqyrutet.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2mapclytw.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2nfewqsuo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2puttgrbi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2fxhksmyr.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2fkjdfhhe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysuotdox.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2gtutxzyq.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2zkiluuuo.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2hepvcsfx.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2budjjauc.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2aauaibir.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2rrmvakxv.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gt2lnaysbmy.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2vnehjswn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gt2wkgnuflj.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckeeazyc.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2znqqpyuy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2xhdnegov.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2waqqcvvt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hggdpyax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlusjclg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gt2sjzubbyp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gt2xowptntc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2qzstiaxq.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gt2msspyejk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2xsapnzgc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlelvvvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gt2tffpwzrz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gt2cfptqkzv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2dvbdhhnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrekcynn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2eodejnhx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2ovmzhdux.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2ctlwdtbw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gt2jwtjjkcd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2kqotirmi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfwfhjux.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2fojayvds.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2jgejsdvx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmuqqng.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwgkhwrw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2xhiyetdj.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2ktjqalfc.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2oummmljt.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2vgdckemz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2sfpqnqqz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qesvumik.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2kdfceapm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gt2tbkgxwak.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2wyvxekfi.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jaypsgxg.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2zusrgiut.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gt2mrldillg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2doiiorrg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2fvzefjco.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ofvmhhtq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2vopumaqa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2zwmmbmte.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gt2dkguxvhq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2avwvpnsr.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2zqxqwzjz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2qgccxnxt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gt2hvlexrrb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2bzoyxnah.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2tlrpvloy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2jegrknob.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2xhaldvnc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gt2lzmxznmd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gt2hxeemgri.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2zbtizyus.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2jfhdgwwc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2oyscrbxa.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2dcniqfkj.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkbhcply.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2ptojhpsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2krfxfgmp.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plbmvfvz.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2yplimzcd.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gt2dltlbeuf.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2scixmjpi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2lxjmuaru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ecfmfaki.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2sxbyycde.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2wrtimeyt.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gt2iootlysb.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxbwifyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2isqqkcgl.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2epnzcsmh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2mqzmpynb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2ncphsrnx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2ptxjnikt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2tdymevsn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2dqkqkclu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2aqbycluz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2lendxhin.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2yjvnkjfs.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2nkcjlrot.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2rrdxmqbs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2milavdae.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2pzfegozj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2cuimjthr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2njnugndv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2rtnefifa.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2gzhspaiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2ojpmvsfi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2kqvfzfkc.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2hdqjgkww.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2aiahlvxf.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gt2iywfvzeb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2xtwwrgbc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2hkcwkeof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gt2okqhwzms.html


<!-- 参考信息 -->