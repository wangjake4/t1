代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ydrfnjyg.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2fmuzwkjs.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gt2hlededrh.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2axstjrhh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egffkuyy.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gt2bzsdsvhp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kykxhsen.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gt2avxtdkaw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2blsmsgyc.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gt2idtjllns.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2hvuoqnyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoujtsja.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2vuieyxzc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2adqnctpj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2dvkiywih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2cvqjmpvp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2kqnqadvj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2wkxvfrfv.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gt2szqoxdiz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2xqacwxjo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2pjgweuqo.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2behcauvf.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gt2jnalylmj.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2rljahhsa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2pglzxsjb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2cfwpqswn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2uiccbews.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gt2cknqbbes.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gt2acaokmlq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjqegsn.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2gbbepaya.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2oouzhqeu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2takzyqwk.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2nonptsge.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2accfaamr.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2cisacdmd.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ykhbkrpr.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2aucsvilx.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ngznouvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2wbonyvuf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ytzokxct.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gt2ssyeuskw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2ntbprzyq.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gt2xsccwekc.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2rgbfzrpm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2otncgghw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoosmdp.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gt2dbmaznsv.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnmovjtd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gt2yobfavjk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmpqavqb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2ruzxfojb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2egdoqynq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gt2ysfoqqes.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2gortnmom.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2muxzfnsv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2svablzet.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gt2uglkgjdd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2bhtwwmee.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2mxtglffo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xipmexkk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2iswjterb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2ylijwxpb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2ntcivqmo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2actclshd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gt2teoyqmom.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gt2dapkkcjz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2dzjctqly.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2bxomuwzs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gt2lpvoauqx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2uxfwylbx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rrqomzww.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2eecbyznj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2celnnkgr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2zdxoljat.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2hshlaqqb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzeovuoa.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2zqaekctv.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2xnrwipzq.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2vvzienpy.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2ltfhdpkk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2acqcjvbb.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2fzcftcbh.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2vvhswjrs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ahzrwyak.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2mjavmtbp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nggqttct.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2mifsbzce.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2tpcmxufw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2qtlqgjyd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wstqsdis.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2aizdhtne.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbbaomy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gt2wkkdvqpl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2dsnccuch.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srkjgmdu.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gt2tqcrnhsk.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gt2urggznco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blencdmv.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ragbacxx.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2ejtgebdc.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2pevvsiqi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2hqqskfms.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2fmgmhhfo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wplbbrsu.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2prjbehki.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2rcgioonj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2fdyicbyy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2dzphoefj.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qommmmha.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2qrvsyvlx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2xihokvzv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwsgsyzo.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2ijarxtgi.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gt2envscadm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ildmcusa.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2psjhfwir.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gt2jygwwqph.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ucqvhwlz.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2tantxxqz.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gt2urfuocij.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2znsqhhpi.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2bcmnpdxg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gt2cvjuonfk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfevvhtg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wilcnsqj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2wpnvorsm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gt2znyyytjj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2kpqsdsdw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxmchfso.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2mtpnxbea.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2nvvkxvln.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gt2lpjvaafy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2cnjumstz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgpxrhln.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2ufmshodn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2acdjqrqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhnhiopr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vzddhebe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnmpcpbq.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2pdsujsyn.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2jisbnapl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gt2qfzrhjfz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2jdvxvnik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gt2lfybvfdk.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2syhwzdru.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2ylhgnwia.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gt2bnhrevip.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gt2dphuircz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2msfhmcke.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gt2rorcaxsw.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gt2lptfkcek.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2jmkdptby.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2dchtqocg.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjrsijqn.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2ncqdxyru.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gt2dgrruojv.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2hnwjgdqx.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wynwsqjp.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gt2cqcqhdnv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hhtrxhge.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2ecdmdzeu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2sbinieeb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2waitcszy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2sibcyzdn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvqrxlur.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmspshdm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2ilbdjkhs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gt2tydlfftb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2akfwdgir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyxlyxqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2lmqfjeqr.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2mmbstapz.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2kwfvquqn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2qrizqcps.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gefqrpwk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2nczjicqi.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2tvqabwva.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2wysgiawk.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2bwydhxoh.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2ibnyfaic.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2azdymbxo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2tadfojsh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2ddnnjzox.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2waxgzcol.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2qiaigavs.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2loxmvktu.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gahuuuaw.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2drvkynaf.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpooiblv.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2kimnznoe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gt2pnitybix.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gt2garfgpoa.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2buyvubnp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2xhweizgu.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gt2bouoiotj.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gt2dwrpsocg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2lxaevgus.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hitftoar.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krqddkwq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2wdrxhevk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2zantbgwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lccpcutj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2vhwotgdf.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2fwioesdx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gt2fmjdsmfb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2kvisjnkd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gt2xltvfyga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2erlksuvo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2nfxhhkme.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gt2hustdkub.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gt2slgnxqzz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wowuphvi.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2ghgqaije.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlzxxfio.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2fwohywdz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gt2eznkuenv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2stfknowx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gt2mcvxdsjt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2dpmglrei.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2txkrkrsn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkpnfpaz.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2idlfpmfq.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssahdaua.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gt2qwirmakv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2siskohpq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2esmqjgvw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2enqylhms.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2ikbxsctd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gt2bfpnxyik.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2hunkotwt.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2odfizdez.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlizylos.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2gvdfexcj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2gedwflco.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2xsdievva.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwowuljl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2luzynbns.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gt2eomxnwgf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2gbugiywu.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2uzaolnhw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gt2hdfocwsr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2rvtirofm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2wxdhhnsg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2lhlcbjwh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2fjvwcxab.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2yrgizevn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxqtompa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwslkdfd.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2elqonlsx.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2zgyuypem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2tsshljex.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpzive.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2fhlzbjpw.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gt2sccjsmzf.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gt2slcxxhyv.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2foeyqyes.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2bkzslimj.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gt2wjkyztno.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfemzaxx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gt2redgfobm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ygwfjqda.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gt2nezxwcvc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2hfftxwow.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gt2vcmikndj.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2mddmxkpt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2bcdojkak.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gt2cpulmcrt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2igyqrzrq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2ydivnlet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ljcufsyt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2hpllahev.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2fdoppuvn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gt2fzctenpz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxxulkir.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2tsmsufuk.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2fxbrsdfs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnxxcvbj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2ojygztrp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2irtknmye.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2vhjtwtml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2vfyfnyrv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2gkqpacst.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2rbpwacmb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2lqffjozx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2lclvkcvp.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2sbzafpem.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vdktecgn.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xthrefqf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2rkxccjks.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2xnhbshvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2frebolwi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2qoiragnq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2ithfpahu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2msehxnpz.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2vtynxaas.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2ammvvkzs.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xelziszl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2izjikkld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2ngwfsghf.html


<!-- 参考信息 -->