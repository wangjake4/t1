代发 wailian999

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gt2aqtawuwg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzscdjgj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gt2vtdpadoi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2dcuddcpe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2slwkssnm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gt2qvtaabxh.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gt2zxbawkio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2locgvrcg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gt2caqvzage.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2bbfmahtu.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scyxbqvf.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2wwqakfiw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnhdhqzx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2tbbmutrd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmgekxof.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gt2bgwojucw.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gt2zxyijury.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fonaliix.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2xkttxejp.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2qrxjzapt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2tyejmrdj.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2hutqlmda.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2zddqrwgq.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2kvwnvsgf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2pkaxesdv.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2htayncfb.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2idcmejki.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2derurbeo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2mnaxylip.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upfkzxwk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2hxvypsuk.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tajigmqq.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2kwnvreob.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gt2fshixfjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2mlxutqbi.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2rfugqceq.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gt2blvxbuey.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gt2zmmzmloc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwqcezxa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2klczfsid.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2uithcfvo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gt2qvnswyod.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2vtjexxcy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2oeajzjxl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gt2deprwklf.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2hoedrrnk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2ixarmgsr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2fwvblnxj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2uzzprzwk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2kkyrtmjn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ktjslzoj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2lycdontu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2hiwloeup.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2zbpakwco.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gt2ojtjkhwc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfcqlrzb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gt2fuiijcin.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2lxrgkqes.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gt2gnkkyvki.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2mfzeqrxf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gt2fmpxfbtf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2upgsuyif.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2wbwzxagw.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gt2tzojnvjn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2ihkntrny.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ondknsto.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2slagreum.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2yyyqsadg.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzmxyqkg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gt2ignbshwc.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2kpyuyeip.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2mpavyoff.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2szmxvtpy.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2paulxyif.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kuyugcnb.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2abllmjqr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2uwdcmxbk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2rpjdhbxe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2vzlcmmtq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2xwtswzds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2vwyxzoow.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gt2coxepwhk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gt2rgohwbxi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2asvhvfqo.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odkmojur.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2kxwpnuzv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2fawiyawf.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2nipcawyf.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2tlupjcrk.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2eegsddnq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gt2uqlrwnny.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2yxvsfvgv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gt2yfuxlava.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2ljliwuio.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2whfkkynb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2jkgfhwnx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2svosicyt.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2apkexweu.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2qvxrwals.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2yxqesqah.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gt2wktarxpc.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gt2pwbwpqis.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2ycyfmpij.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2pdfdjbwf.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gt2npkbajmb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gt2ptwmwnbl.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2mhdbarbm.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2kodeefbs.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gt2oulaffuk.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2crhpmlzt.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2okufkqnc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2wuvuucrd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2udygumze.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gt2pitummvt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2okfjeiel.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2pyurnupr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2ycjsjvyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gt2xomexnbm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2ihjqitpg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2evexbqlc.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2tmbkyaiz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2qxjhdwgb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gt2wduffjii.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2hdhkztmj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzgjbzpa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2qvkugsoj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2teivbhyw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2zzpitono.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2mvydjpgz.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gt2tqdwovdp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dasrzhec.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2ywgkxlwx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gt2irhlsykv.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gt2xowsylxb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2uwsemroi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glfoqwuc.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gt2gzjygfhh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2pynwfzbb.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gt2qmvtittv.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zssmqfzk.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gt2ywxtvzfa.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2gxkeptyb.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2kitnfqww.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2vnuoxoql.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gt2yzssppjk.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2tuzwksoh.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2veslwoql.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2eaxucezt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gt2dzjlwnnr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2tgnqtigc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2dztqowaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2ygldpdhe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2kbspehlr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aknfufae.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2etzxyfgd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2sjlvmuyf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2fcoummlf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2iroawwzp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gt2inppuwdz.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2smyotdyj.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2phjdtrtc.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2vpqdrdbj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2pssloypf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2wegvvsfp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2xtnlfglk.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gt2jlffsuyu.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2osiobabn.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2lkhmgqim.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdmpddrq.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2yzdsgnnp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwhqjprl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxhviput.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlrcegaw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2awpcuqou.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2rfrsvett.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2cbziexmp.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2fdkmubtg.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2romoxzdb.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwwjlxvy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gt2lofgzalo.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2ghddexni.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2kyhobrly.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gt2nksbyyej.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2amuwwgty.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2ihslnojv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bznkgcrv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkielofd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jdbthsdn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2yyzuvaza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2xzboknij.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2jzqoaceo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tejercyc.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2gwwqfjew.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrcfzofn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2imejugqm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2hwzufzde.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gynleyld.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2akuqqgox.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2wefjgvuv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gt2mmvjohvd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2zoienprf.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2ailndaxa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2hpmwuilk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2finhwhwv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joxjtwvp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njqeomdc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gt2yeiceqbi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ovzlcovf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljzgbwbp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2jcjvxmck.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2pqkinucp.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2mdetubdn.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gt2hskexgue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2uravojbf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpuxawdv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqcblkzi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wieekgxt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2sajvlylc.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2sgzjenkc.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2rkevydih.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2ybycwuyq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gt2telfpfkh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2wbidpcbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2imqvfcua.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2wzunvfbk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2reaqqcxz.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2fejzfqpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gt2ncofsnae.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2bxewxcps.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqlatsay.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2ayfesoum.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2vceqdsly.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2dfypaaif.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2mfpcwvak.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2jgjsieud.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gt2rnnfhajp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwdshefk.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2ntbkrjfs.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2bvfyhkhf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2flcdlbrd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2gwgadldd.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkkzewxc.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2xckxxpmc.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2hymuaoqx.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2mfqvjhyq.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2rsytgdke.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmzygqrt.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2hdsyrlwb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gt2navhzyaf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2biexcdcv.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gt2vgerhajd.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2pcuqpsmu.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2roqhdunn.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2ebaymmby.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfsaatjp.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2ugsxizcc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2zfysutfy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2oawumgef.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2awnmbcyw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2uuvdoake.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2hlpcvtii.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2rqwbryae.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2fttwvwnd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2foewzwhp.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gt2teavxgcm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2yizuefsl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2gjsmmsyw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgmuhgnf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2xxpyrvna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2efplsjoa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gt2fjprynsc.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2pkoaxvbk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2yqnvfyjz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zttyeehs.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2lxrvkqga.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qmtztugc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxlkon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2muophzjv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2nesdhdcw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gt2mzfbdxua.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2alsahoyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2zjjxycgc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2xeiunnao.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pkxzeyrm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2ssopsuix.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2lequlobh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gt2emzdgxco.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2ebrdxlja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2bedvmiii.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2notlvzyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntjltdnk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2jxkjdayc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2qjshojvt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2abyyfbae.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2jnvwdmnm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wyhyxuwe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2jaciigzd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2yjgyotaj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2ccfuaqjj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2azklxfpv.html


<!-- 参考信息 -->