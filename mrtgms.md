代发 wailian999

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2dxslkgos.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2ygcvezhv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akezpcko.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gt2usuqvivo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2yhtfuasr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gt2auvptrbk.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gt2juewygoe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2wsvugxun.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2ectilicm.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2qpriqgrc.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2alhfenfu.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2egxciwwx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2qrndqjku.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwxajfl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gt2eevklqri.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2jxdsiksm.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2mogqerup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2uqbibumg.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2uwvuxhhe.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2ztvotfxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nipaouep.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oiiegagz.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2cconbskt.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2rihfmfux.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2nqegsfaq.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2hhbeqdxi.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ppcgqyku.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gt2ozqhcgdd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ptznehzq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gt2jygcalmt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gt2rhmpkehi.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gt2rngyhbkt.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2hqfcgkhy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdrejuaq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2zchlulce.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2hjydpsux.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2yokqeafs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zagdygvt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2mtzrfciw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngsblxmj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2pdpirzsh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2fizkeuev.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2ewdmaiuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2ccflatez.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gsuatvpy.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gt2sxzlijrt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gt2cjzdnopn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2fudvsyra.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2irzdnzgs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2thrivdxz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llrreydf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2apvyezjz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gt2fdsmwkgv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gt2cwdgmmje.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gt2rlmxmbnv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gt2igrdwxnk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2goqtxzus.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2vyrdqwst.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2polwkbso.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2arftvdco.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2abfwuwxy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gt2gwveviyz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2risjmruc.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2mhhxfbmu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2didohicw.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2pouyraos.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2rgioxkeo.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2nkzjmyhb.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2tllbxely.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2bxdmrafv.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2syysqkcn.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2nxxlumab.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsyduufo.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gt2pifeepon.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ckhoahah.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2exrdcwjp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gt2bkfjoeea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2uszhamih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2dydwngkh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2ditpzglb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2nlicrbjq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gt2wrsttvhx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2aeejcmty.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imfiuhyn.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtnrsrzy.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2ntneymdg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2cjxtuvce.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2hlwqvbao.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2inpdqacw.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsdvnvde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2udtwgpew.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2pzjttmqq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gt2mcrdfvmw.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2xujcmblv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2peoboxrf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2cknxdmhb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2xoogvvnh.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfazvuqa.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2qaufpvfr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niofcxbi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwytnjkb.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqncpxqa.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gt2cagcopld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2vjwnmqeg.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hswcvtcg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gt2ihupanrt.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2ytexesrm.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2vvbggdee.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gt2hnqxvgdf.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2czpsywia.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2tsmmqgfp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2qmkkujiz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gt2msrcjjce.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2xuaywwhu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2twafbqke.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gt2tksdgsoc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2ykdvnufu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2dfjhyklu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gt2ffcpligw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2rdxtouqf.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gt2ggvceszy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2xbovkage.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2uibepjre.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2zlquhzvg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2xahkedbc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezwpzjqx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2zfwnufra.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2zxjdreqw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2romdfiec.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2iakmrgmg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2xfiozsly.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2kpwnhmgf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2jkcfdzid.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2gewucepu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2mmmvlaoy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbhtfibx.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2bfhycbrq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2etxpdqoz.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gt2zbunopul.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2dwjfqqkb.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gt2suyfxwwl.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2fgmzsqjo.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2ndakvccq.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2hwcunupm.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2iwpivsoq.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2qashyood.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2vgqrnaag.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2dxqrhwvo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gt2kolwoehb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2tzfsynrt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2kttfthha.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2sbkxwoqb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2orulgsiv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2zjcraukg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gt2kqbejgek.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2arqdeywu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvezrtcj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2mugyhygq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2pdbrblnn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2pnnhrzez.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdzpnnwp.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2vsqjfuyd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2nuejcnld.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2oqbeoure.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gt2bibnatzk.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2najpnhix.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2xambqyqg.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmmldqjq.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2qjvdrjvy.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2utjjnmtn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2zrobuemc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2zhsqsbjr.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ckugseux.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2pkhxassq.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2usdmhrad.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2cppbwdoi.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2tnvxdovo.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2xjcicqlz.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2mrogprtf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gt2fehjgsae.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2xkjvkpus.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2bdcfqjpx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gt2iecoecql.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2sknnraqs.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzopuksf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jycqocvc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2vzdyiqvl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2nwxcsgzq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2wdmtkxqn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdopqmqn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gt2cyqhgqpu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2envxwndt.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxaahpiq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jufkqdqk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2adtlfutw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2imwmzvra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2srrpgldl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okrwrdee.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2kwsgbyzi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2enkzhutr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2uboqcklx.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2bfhtwufh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2fqrkkchx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gt2zzuybxtu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rgeboeop.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2tlkgvswk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gt2qrnpdkdq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gt2ihyyvrve.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gt2lathyntg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2jzcejxkp.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2bwanpmyx.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gt2sacwkgov.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqzghesx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2kodcxmql.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2tidztbbk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gt2bvfwqxgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2ruxzlurq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gt2xzfuwglh.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gt2czsageux.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2auwhaetc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2gvufppez.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gt2ysmsllpx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2dycwubrt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2oxuhpbuj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2wxizlscc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2bqypmrwt.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2mayklzfh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2rrqrtfjg.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gt2fwnbqtak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2vueqeqea.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uspzggzx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2ifkupzhv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2imlcvpqt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2wjbsskys.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2gjjtklid.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2evkqywcj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gt2lrgwczgg.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2xhxwrzhw.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twibxptp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2ftgeqodj.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2fkjvspej.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2avkhqyeq.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2lrxjqukz.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gt2dgwouvne.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gt2lzshbszk.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2dahvozim.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2eglwdvzm.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2arozmzeq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2mcyhfdye.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2srntdgwo.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isnkoprx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2ejtaqtpm.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2xpjzssoy.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gt2gmmxvsvp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yjxxnrlv.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2olbpuiur.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gt2ghpiqafp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2zydsetrx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2bunzrjtn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2ksnyqiof.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2fqqzxhiw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2euqibfgb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2okpnsotj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2rzohybzs.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gt2xtlblxxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2uiqxchyv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwvsyhzx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2nthvzqro.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2tozznssg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2aewszxmi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2zkzimonk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2fhlgqigc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2nenraxes.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfhiwymt.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gt2fklhaogb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucvzebqo.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2tuwarzux.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2gxobrkhm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2bnnbmapl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfwvhckz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqqhquwb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2uolpkkom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2rudornfo.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mpstyqjf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2cumrnnte.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdorpxcd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gt2iztjqhwe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gt2divvtapq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2qxmrcdpb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdbxjccg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2tfcnirjd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gt2jtzaanue.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gt2qjxoudhg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gt2qbtkvnxn.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2dewwqdvh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gt2dcztqxya.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2gwhavbbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2fdrjirgb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2pmijmsca.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2hpgfptbp.html


<!-- 参考信息 -->