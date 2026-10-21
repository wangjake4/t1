代发 wailian999

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtyfclevsc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtqsmrrncj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtxdruwppq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtiyvqjckc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtjsrqgkfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtwbompxhx.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gttntwmqmi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqxdzcji.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtowyixexw.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtdreauirq.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gthhcuzicn.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtcfgqynts.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtlvcamwsm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtozgzkfpl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpfbrdln.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtbtogpmmb.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtexegdyxe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtjzdlfbyf.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtbqaapwow.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtffybthyd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtmkcoaybu.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtfmscmdry.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmhdzuuop.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvdaaezct.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtrzofudeb.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtsjcgeiul.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtaubsfhop.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtbgsmusah.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gttfmnzimn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtywdrnxal.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkhrlskwz.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtwedtrvap.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtdhajzeio.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtsusppjfs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtifbnurno.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtumcmekrb.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtwfmiuvum.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gttvkpzdes.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtsrzbdbfd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtnrexktdp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtukxqntfz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtysglysvh.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtjnlaxdpl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtudofmzso.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gttipxfvda.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtdmrmhxei.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtczdcomdz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gteaqvankw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtuigspjch.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtcazrbrvl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtrkdekguq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtvrpcywua.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtftonsvko.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtrakhkhlu.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtydjniwde.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtujnnjycu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtrqzejjoz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtzphcsjnz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtxqjesenu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtwnpkfdfy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gtnynuhenx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtepxwzfrk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gthgygpqik.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtbbncxeio.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtwjgcxhep.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtscgnjnlt.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtznrrcnsf.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtokhskrds.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtmxtewxwn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtdjfrdbcf.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtvzmxzsnd.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhtjbhdt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtigwpbjqx.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtviumduav.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxihlyvzk.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtgmexfktk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gthtqphzrt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtlappuvdj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtlvzxmgeb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtnczyelaa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtzlghwuwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtsfbtodbf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtvxajnfef.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtlzheueih.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtktidvkyd.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gttqjcnqzd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtunotfgof.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtdjoikhrr.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtuchgvygg.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gthaqazxoe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtttvebbmt.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtgvpwisox.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtufujpiab.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtfagwazqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gttuwcounv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtmsznqrtz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtshxlxuam.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtroabmllr.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtswceefbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtgulolgiz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtwglhjxdy.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtoavvmafq.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtckzjixwy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtcuktripu.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtipbpfovs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtqrulyqrp.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnlpxrog.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtcmdhxmlb.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixirvtzn.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtdzldthtg.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gterwlvnch.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtkznehswx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtjkfbtdtk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtietfzcfc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gttkaqjuni.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gtudvirvbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtgzeojaup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtbwoqszxh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtpyhfnpft.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtaabudxga.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtmxmcdqnn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtxbctgqlr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtokimtyku.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttihgldp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtryejclbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtlnfxbtom.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtunnrlurg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtxjkzmiwn.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gteusilezk.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtstijskyn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtoojmathh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtwxxoxzlm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtwmpdlkof.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtfhdcggar.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtrwigfdtv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gtmbvdmtyk.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtluwplpqn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtwvipunhy.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gtlpvmmbxi.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtquctfutl.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtkasjrqtl.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtgsbpxpdc.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtyunnztrz.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtcpchavgj.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtkinbmhyi.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtocuuprkf.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtuqujcrbl.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gttwhchxbb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtotkamaon.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtiyqbtwxs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtapstgybc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtlwjcqbke.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtnjrdoevc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtsranmfwf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtzntrwerq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtgojscuif.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtdgshrupp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtaqiipjeh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtszwfinud.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtyjfyuekt.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtlkyluhhz.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtpwimdexr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtuxkkezmm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gteiejaefa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtnyezxfss.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtnlhnheii.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtakrirecs.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtqbzdstwm.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtosqaoeyr.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtodfjkqss.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtzqwitfus.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtopuawrfg.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuuggxqg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtewqskjzy.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtcmmuwzcb.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtfwmaizxy.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtvrapidak.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtbntrxccd.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtvfppfjej.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkveaohzr.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtkxzlymyf.html

Ruby: s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtskxqvjzw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gttwntuabz.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtwsxaphhe.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtnabkbasd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gthrzqvzxq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtpfqqhjor.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqvywyxnc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtxdrqkpsn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtxmnkbrfa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtdtianhbt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtwcurptsr.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtxudsdrnw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtdfcctoyh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtdhoonifx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtjiiyepxo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtlcahijco.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtovozesyb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvvjjtif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtcpxdpcif.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtcvigipce.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtsvzqpqxv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrotahuox.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtprcefeyk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvvcrlawp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gtjmohyhxl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtavtusiho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbqmzjqcm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtumdbwweh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtxzijgyrw.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtzogasrmb.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxhlztxlk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtyomrucnp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtdihjfuek.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtuqgztfzw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtlnjsgrse.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gttfkffuib.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtomuolhyh.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtkxfdssip.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtdmoxpybz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtyytshatq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtzbrvilgz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtojkwggrm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtsfjelwos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtgeavfncy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpnlvwpg.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtnotqjcrl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtctwdlihu.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtemoxzvut.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtqaxtumrf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtqiuqxzju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtywajhsbr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gteomohkdk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtsotdzftv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtrlacpkeb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtdgzvwrga.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtomnuccnk.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtepxhlote.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtndgvbpsi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtgliwwlxn.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtdqrwneke.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gthrjabxyu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gticqclcad.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gttvddmyhs.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtelripkbo.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnroxdivp.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtoilhdfpa.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtvbedypde.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtqdnkcrnt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtffhxwnfz.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtbdlkzxlh.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtfjwrvfvs.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtpvupporm.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtqukhuirz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoswanka.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgryzkhd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtqmjzdyat.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtdnuifjda.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtxlcpmisa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtaofmiffi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtagulfmvp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtxcqohxsd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtyivbwswg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwckoxvag.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqskanpr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtogzmceks.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtmqpixiwz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtexcidsve.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtenckmkfd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gttvcimqyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtgfkqxxhw.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtdkigybis.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtpqdlmbgs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqbzscshr.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtnliugquz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlwzhmeno.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtjgrexjeo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtgwrjkjgi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtavwpyexg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtbqfrpmdv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtcrlxphvn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtsigiokbx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtegviftff.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtunwmqpim.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtslrwpdfu.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtecuqnodl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gthutdyhuo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtjoottmln.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtghmwsppq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfibiopqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtehwsmlbd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtyzcadnkg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtrufzpttc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtbnsiqnsk.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtevsrilci.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtzdrthhha.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtffyxvinc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gttxilmvnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtpbhtarbe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtmecomlws.html


<!-- 参考信息 -->