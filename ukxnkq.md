代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2kxewcyza.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2eieipixx.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gt2rlbblayk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kotlvztx.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxhefxve.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gt2zsixnkyj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2qiisbjjr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2kctjqmau.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2brgtxcao.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gt2mmbcmilz.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gt2bnvlghwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2akelqxwi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gt2eoqghoqd.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gt2tcdrtojc.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zvbncdsq.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2aszbihff.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2mpizgfan.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2mowvxbin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2xirehmrn.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gt2ndpjlrhn.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gt2nfztqjac.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gt2hgfcnfri.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2tufdjqmp.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2neghjkxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuhweuaz.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2iibvveph.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2maytzbgr.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2auwdldgp.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2xzzyjrju.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nxqqfcwr.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2uhiscrka.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gt2ttwpewpb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twduutgj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2nnusjmdv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2kxjuizwf.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2oepohifs.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2murusljk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gt2khscjvwj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2hmqdpsrl.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2scxqfaok.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2dlhyknqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gt2fiwqrohd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2yiiqbbri.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2oghbcqay.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2rbwgovtk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gt2lvoizzyr.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2bmrsbcgl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2cpjgfgdp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2ajbbjeoh.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcypclni.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gt2vczqlcfo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuanmzzf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2gdendzrg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2yhwcxalq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2oecajkco.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2jktjsoic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gt2xtrjwmeu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gt2ymatqyrx.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gt2ylwssepj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gt2qgpkcday.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2rzmuquip.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcvshflg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2eijhtxiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2hsiurffv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2akdbeudn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ekyyitqn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2dfwsnccf.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2fbokkpwa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2ifmrdags.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2blwwznbj.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2lrghubat.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2ccalnhnv.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2ynolisdg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gt2srtysiow.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2rphrbbtn.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ythoeplm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hqqyqcvv.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2kohqdfom.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yqbxjcrd.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2jsanbzxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gt2ayyyamie.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2kflxhjhd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2womjnmum.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2hjwgmkvq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2aunxrnkh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gt2lwrcvrey.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gt2joxbvbso.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2kalpzwvg.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2lnwibxcn.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2hdrbtofe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdornnux.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjrsffhb.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2axqelner.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2mhhjzrto.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgfjurmj.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2xwgqzmvz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2zzqvecjf.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2juohwpdh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gt2efhskprj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxjmeohc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2magfdors.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxfsntzl.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2kjpgwtoo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2ecroseja.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2uskfdcfl.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gt2wrohxsec.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2zhfashwa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daria6918.cn/Article/details/gt2vzfvvriz.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gt2fqkmhumz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2okwmiqah.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2kzcfowmr.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2stpidato.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gt2hipyxyvy.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bherzpms.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2jmfqpzma.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gt2xzddfvxd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gt2titevhnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gt2yrjkmubn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2ycrckqja.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gt2gunotydw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2vnpnbzjj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2onhhvecx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gt2wwzyzpyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2fzlksuxj.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gt2ttxqjreu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2uakfedpj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykovjiyf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2zehaafbb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2bwidlrbq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2pfadxazb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgrwnmot.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2vexchiet.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fukrsywy.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gt2afamdxlj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2gbtjwnqj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2cxmvxsuf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gt2mtzjdwhj.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gt2pmrggvfk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbkzcqgq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gt2baplogfm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teshrlqb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2nhfwippi.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2bmajcfxu.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2ljwedbcq.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yoopaoty.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvfzkidq.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2cvwtztys.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2ueveprdf.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gt2zftdgtcj.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2lhnvbtpm.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2tjmduhbq.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2ffvvaacr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2pudaowhu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgtabzkm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2oighetna.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2hmyiicon.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eanbhytj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2vnqzpjfh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gt2zwwsxvos.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2gokabpiw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gt2dgfqzztl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nznrvqjc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gt2lomielxx.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2ewyeplmj.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2rrylqnwz.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2ekeeewpk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2zuduuvbm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2slsgtebu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqdtxqiq.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2yhlbfqmy.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2ssowbnnj.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2ayppfnqj.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2lmwykpqz.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2xvbzpyif.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2wazvnyyi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2bzqrcujk.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2iebsgrjs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2urvowald.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2ccdexbli.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2apmvbpwf.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnbaisul.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2eowptsvs.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2atspvvsw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gt2ujtpymgz.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2lqkrgsnj.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2zutizowg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gt2rnimfnug.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2blcewhaf.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2zkfuvzlo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2tobqhjlr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2bilvwyqg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2ppmfrjpx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2asiavbqq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2amtapttz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2yfetkxef.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ozgcqqmj.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gt2dgcrxuli.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gt2hpnwinsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2bvdzaeam.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gt2mwjhsvzc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oekzwtxp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2wdmluwah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2syvmvptz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zshwymqk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2jxnpmrbq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gt2pjoaxiuo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lndtrvdq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqitudsj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gt2imftjmib.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnwyzvgz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbjyuzay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gt2eflkhuhb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwciauqz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nggjnbeh.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2lbxwwfcu.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2rtmiyzaz.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2ocgpiizm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2dbpuavsx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2kmygyboo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2lviskzor.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2fwlxjyrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2brfdqslj.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnoihwtv.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gt2wbhjbcpz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2jpglicij.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2apwlobue.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oncecqvz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2nnvcrohl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2svuvjgec.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2ertshtln.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gt2ulcrqciu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2wlhitzby.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2kliehpao.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gt2xkbzffev.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gt2opdlzfga.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2aqaysxiv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2owxwrurm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2gedlmglp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2ezykqgfe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2phnxsbbl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2uepjdcta.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2bvkrhfwn.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2wcgivnxx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ydzfbvuy.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2uhrbujuq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ccadsgno.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gt2kyphfnyf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrljqcwf.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytwhjecf.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2fpttcjkk.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2cbkohasw.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2bagpriaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2uvvhvptk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gt2arkjrqmw.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2nzicimye.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2klzpyfvo.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2ebqxvxot.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gt2yqdrkzgn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gt2gvjvlkws.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2iolbkmjt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gt2deubzgzn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2mjtxxhgz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2phibedlm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dynbbhzw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2geptwlvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymejxotz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2qsglqjpp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2clirelwc.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gt2sjwoaxzv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2gmlbhncl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2tfycbbtq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2khzodjhy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2mztaromy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2jkjntrvb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2oienzayh.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2hrctegmq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2hxqrxefh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2glhmdqox.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gt2zbcrdzbq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfxbwzic.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkohfjdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2hcuzvhfs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srnxrbui.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2thltmmkd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2pahsmsjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2udbzjiff.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrnzwekb.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2peacxtic.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2atxgxqgj.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2labjsfzb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gt2drlkoqfj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2kybkapzg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgysquiw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlcwmdem.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2iehppkyw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2zgjkpegw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gt2gnrbdzgm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2trxzvsls.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfbobquz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2tidsdiot.html


<!-- 参考信息 -->