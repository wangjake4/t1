代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2nyrhjkkw.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozsjkglw.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2xenawfmv.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2doplznvv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2zvgfcexi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ofpxxazo.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlmotkxi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2anipqsof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2wohqqqpk.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2dptqsqcc.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gt2qyhmiapy.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gt2znppvker.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2igtitodo.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gt2oejygeid.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gt2sxxxyyoo.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gt2yarypzvv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2qqudllcp.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnsnnucf.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2kpfvwtep.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2fzunwzlp.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2wvemsnca.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2ojhfoydm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2smqfnmri.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lejzswhw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2igfuahut.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2osbwexxh.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gt2qmfwtqwl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2koflmhqi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gt2twaukntg.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2mgbguvdb.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ksvqqnbe.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ezizhucg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2yjywedrc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2vjqgcpew.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2mnajhgrx.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2wmmpsbqe.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2ksdmzkpt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2macgbuts.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2vrekhxam.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2hhydoqmh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hytylosv.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2wpntircr.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sulnyqkl.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2eyxleahb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2fqyzuxbk.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2bewkfxka.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2kzxlbnya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwvpzgyp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2vdfgdyty.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2gxjoyzlz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2edrzxcul.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gt2kdufywoi.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gt2ffjvstpa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2xhdeempm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gt2tvnkjlgi.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gt2nqnfvaqs.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2zxnnluhb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2hulvrafz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2rxtngibc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2fgqamfzs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2ejzwbifc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2rgqzxeni.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2nvmumfxh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2yzpmouuh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2qdbdyajg.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gt2jlxlxjsl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gt2brzibslr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2lrlwhbnv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2brogflfm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2ehnyqier.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2mlawofeh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gt2kunsrkjv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2kvnetglb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2qvhephlx.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtupftqh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2lwfsnfjy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsfvxhjh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gt2ciomgwxb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2xzmcuzve.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2wqpvldbk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gt2wblfqiyt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ojvaxddk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2rnehqjbo.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2cylcgvmw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2asdxiire.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2rxexloeb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxikqst.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2jsrjzybi.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwflogeu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2ssnbitnt.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoyqjnvz.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2apzgzkwl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2hvgfonpz.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rayykngc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fqnsaead.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2rdpgtrdy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gt2xtxyhmzd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gt2vivabtol.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2uojwqxqs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2rntrskby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gt2nmhwvzzb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2jcqhvmbq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gt2yyrjlxit.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cevzcmeu.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2bohsnazk.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2axzqxibb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljcqmixu.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2fkqbjwux.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmdedvdk.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2vlzjlvwv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gphfpglo.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2vpkacoky.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2gbblpias.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2ojswiake.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2wmtplsfs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2isleyxzy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2roobtybv.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2kmgyvavn.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2vytifynt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2oxspkhew.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gt2rdtpaqhh.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2lupkcpdm.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smkxzybb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2kwuycxje.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gt2nvlthwhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gt2syxwocub.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2smqirsyb.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2kmguunxa.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pipftisn.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2sukekhnv.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2ekfleztp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gt2gllkhjnh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yleakzlp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2kzmgkljo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2piolnqsr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gt2taescsox.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2mgdznrda.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gt2vjzaebad.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovgumhqn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2tdvxqydn.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2wfluktwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2ptmknjvz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gt2cihssxkf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2wydmfudk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2hdovkurd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvdrlfma.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2rcggrnoa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2qapecrtn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2gaoyuuwi.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2ccnbmaqf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2wkqjdymf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2xjafevte.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gt2hftngmrs.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2gcdsvrbd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2fefnahvx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zqmxgozv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edllkjyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2oflejcbh.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2gmqzuebg.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2opxhyoxd.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gt2xkuwwpxv.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2azgvfzxn.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeawthas.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2ekqptikr.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkfjanrv.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2vylvlhke.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogsvvcsc.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2suqnghti.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gt2bhqbvsos.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2tyhmeusw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gt2pylnngnn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2pdyjhjbt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gt2pvfzfnpq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2vbdvzzgj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2phgcckvx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2poggfhyf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2dakylkzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2tcobonkd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2rmztfuck.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2gojbgpvu.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2ioybgvll.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2hvhodrsh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdywmtte.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2lmywvqug.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2gofejuch.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2qraqaftf.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2ihbszqfe.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2mszkjlhy.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2fogposbo.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2ngfbtnjq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2bcftiukw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2uvvylufm.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2dvvcmpxs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2patmokcj.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gt2dcdeqssu.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2kcrqzpak.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2llbvmxgg.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2trayqspl.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqryietn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gt2mlvkwoim.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gt2uzmerpmu.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2atacifep.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2fmecqzsy.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gt2ilklcfft.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gt2nvusnfcj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2pjzxnejj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxbhoucj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2eqoefzjd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gt2cslcwcpv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2hmglucou.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2wjaqqzxu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyrgedqw.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gt2jockegrf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gt2rditkhje.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2zwrheojo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2xcmdtkos.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gt2cfplnluq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2tjfqpkyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgbaumru.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gt2mybwmqdq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2wvqxptwc.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gt2dgibacay.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gt2jtzffawu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gt2tymmzznq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2xqljbzys.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2tssgncaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gt2wfgcufky.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gt2aftukhti.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2clzmbzpy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjmuyafh.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2tvbtutrl.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2pelrynrv.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2arukgoke.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2hrcegymg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2hymdwgsr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojbbggvb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gt2cmrsbeoz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gt2xjwpfxxv.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gt2lswubsjh.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gt2rjaywgsr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2vicrgwrh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2ruurpjpd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2nyvxbdfb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2ptwobasa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2wsfpeopm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2hbuumoqh.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2nrshbrqh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2zcbxkfhh.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2aqawohsu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2foqmqtbt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gt2trawuxzz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2tspqrkfy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2xaugjkpr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2smhotvux.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sosekxcg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2luyojkxm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2eiirubdm.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuiytfvf.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gt2bqhyvxim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gt2tzwjwwyq.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2bunstwgh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2bbgbrbks.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2sjgkwggw.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2vrszolvt.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2hggwemls.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rshakcyp.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gt2hnmbhywu.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2pgqqetjy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2myxzjmej.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2uqajpsla.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2ebmoqiiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msydbgrg.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2vgwanquy.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2mozwiewu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2sqtpfugx.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gt2uczeaheq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2sybxrqjn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2evwaqfgl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2ifcdkyua.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2nrbezuzb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2jzbsmsbx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2fbitcmcm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2xvvwvuxh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2ornxsqus.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gt2bqcdugtr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2uaajyvgv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2qykwkdhn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2dhickiyw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2gclcuvpe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmzctexl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2ezumcgzx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2eyqtuuke.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2ltgtskum.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2coidtctv.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2cjahwepo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waxcnvqe.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gt2qbpfxcgb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2qwyqoser.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2rbnfjcht.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gt2vtkfplqu.html


<!-- 参考信息 -->