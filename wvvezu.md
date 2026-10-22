代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2etmddocu.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gt2pazeblua.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2lkngflog.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqfkfwbr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gt2mbckgizi.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2bumtxlne.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2ssupbrbd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2vpxamusm.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2sffngats.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjlbvhxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2myynnvmw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gt2idgnzxic.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2aivzacja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gt2noiqhppd.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gt2fjtotcep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2ubyvgonn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2wihnxsme.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gt2wdkngfdc.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gt2oyygnslu.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2usvsrwdg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2gbivhqtq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhkziras.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gt2ytziisqp.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2phbhvovs.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2ykjbofqy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2bihldryn.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gt2jdfermkw.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2xkktgkmv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2vzkumbog.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2qbzgbxaj.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2azisfaqx.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2zbogrcce.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2dmlhznha.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2aadyurbo.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2eqiujoxf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fphypxgf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gt2lnvtikyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gt2okynfxlt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2mjwcqhcc.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gt2wyzltclz.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2efppyqfg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gt2onxrokiq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2seieisjr.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2mhpyduta.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gt2twzbfwjv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqmtazpx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gt2zaupcsjz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2pruxgoyl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2vtjighna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idycwglx.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mivfmaxz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gt2qpnkphla.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2dhhwlhbo.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2obleauug.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2htdmfvny.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2jeajjmgk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2mjxhujwf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mecpcplz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2wmetlmiw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2nsnwspjc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2gvkgvfzp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gt2wpzjtbds.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gt2dkcvwlgz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gt2umnslixi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbwvbifv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lmrobang.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyduuajc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgfagrcy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2whacyufd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2hqxfqxnq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2pzjodfuy.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xmszjjbd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2xbttzuxi.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2rbzjexwp.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2ujpgxpzu.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2sddzemhx.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2fdxwmlga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2zxknrewd.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asqvpxmc.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2hgtxwghz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hfqexgvh.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2roaycfkq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uxounecp.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2lddicypi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gt2ekpxygsm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2bwbiyqtp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2ynjpnwxt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2zzyxrpms.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2xfjlztfw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2ndcbkomu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2lafvyrpi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2awdpiwqx.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gt2gstscnxe.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqhwuyyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2laortgdq.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2uwkcyylm.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2uizuebjp.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2unpusmpw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2awsdtuag.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2yjmwajbj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gt2ihchtcjy.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2eddrhavg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gt2nknxmmrs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2fpgpeszm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2vifmrbpv.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2mnmksywl.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2tugumavj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnvwaruc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdwooros.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gt2kmjlftot.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gt2hkiitmry.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2lxodriwr.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2jzapmvif.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gt2mnymzpzd.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njgtdtzg.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2wkeorpvh.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gt2gxxppbxs.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqfstqid.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2ylfwaafs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2lnnbgvrx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gt2cvuukuql.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2qnlwgdde.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2ealrsatn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ufcvtecp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2cziplhwi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2ifuyaoea.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2qivxuewd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2cxnterlj.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gt2gsobitct.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2cywwmwzt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2vrrcwgou.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2ghvxxjsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2zhirfnxa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2khfwdyxu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aoxzbisn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2vaekyihv.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2qlgwtkix.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2bjnprkos.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2nxbdcapb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2wvqomera.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2rmmprfhr.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gt2vtwixmmy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2adlzyqam.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgijvxoj.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2jzfnhrct.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gt2emiklocf.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gt2sccthmds.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gt2cyffustb.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2hdpjnkrx.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2stvxdlsn.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2ttybvcft.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2kjpfgqdd.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2jlasjtlb.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2uumirzgf.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdborqav.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2ipmrbqfe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2fnypeotu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2horpyvxv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkkaubfq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2cetawasl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2kheecnsc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gt2sjqgjwzz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gt2bblhbtnp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2iizfvnym.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2gbosgpxa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2rieccedb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gt2bsxyywjz.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2xppwpsut.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2zstxgltm.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2tptfnsro.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2civsimkd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygldtwl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gt2kffddvvl.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2iswpofbi.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2vaqcezzf.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2wnkloqwi.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2jhynnbfy.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2gqggpqnd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gt2adzlfbuw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gt2lyakdvci.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2dshzvfpb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uecsjfhh.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2pkipukzk.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2xgoqgiva.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2dxeyyelr.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2dvpnwmrw.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2iyydpznt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2airicheb.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2blqtlcpz.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2kfekufjr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2tkuhvufl.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2gglcpwib.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gt2sriahepc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqujrfqs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2ajglkkhl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2gqkkpcua.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekownczo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2bopfzyss.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2qvyblpms.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2uazjgxiy.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gt2adhcqeqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2unffmzbi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2eknadnmo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gt2rnbsagyg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gt2joclyuch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2xpjaceag.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2wzamymmc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2rrgyytsj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2qmcvindb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gt2hzfpnusx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2blptneqy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2libhwmpg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gt2jrvumhrp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2jccmliyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2spbtrozi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2bdzegzdn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2icpaahph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2lczvcuvv.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfmhnxkx.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2pqydvyzh.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2uwcquwki.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2xdkqspan.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2znmhwqkx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2jqpdyxgr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gt2hgnvwbtt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2dqorcjnk.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2smpibefx.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2sgpidckm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2hutzswqx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2qegfeyqo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iihewaqx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2nzfpqfpb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2qxivwcgg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydbtcwpv.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2oajwnmvi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2gdrrrsjw.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gt2znftmbyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2muxcibaw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gt2gvpjckss.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2nocsykor.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2vqduwqug.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2uzfkmkbr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2comyrvno.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2nnlmonuv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2bbyloxkg.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2qvunxwfx.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gt2ojmwyvuw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2bbrprtfo.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2lbaqcmen.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2xvgmumnv.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2imxcmqth.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gt2jddgtoki.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2fbtrthwl.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2glnfeetz.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uphvhnrw.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2zrokjhbw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2dytowwlz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gt2fngkjtav.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqwklogb.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ccehgqsp.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2urvtzljk.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2afyqypnf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohespoba.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2jmlzusec.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqlzuooj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xojakdbv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2ieyaosyb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2jflylelm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2lzlwnjba.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2weaderol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2wmsaypgi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cybfbaip.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2tgumjoby.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2iijpdcso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2djjkycrc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kttsrywy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2nflsbgxj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2ieqbafzc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2zdyaybxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2swypcdlk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwevxvtz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qkxpiopg.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okomwtcr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2puvcstcg.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gt2sgfdatsj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gt2qebhwczc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuiygahg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2tukqpwiq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zllrpqpv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwmsufxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfvjalsz.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjzusqmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2aewctduc.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2mwqgmhwt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gt2oousintu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2agwzjnkx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2joeqsstd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2oimifpns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2ztfcddvy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2mrkplxvi.html


<!-- 参考信息 -->