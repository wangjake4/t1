代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtuotrqtvi.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtviixolid.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtyzjvfxaa.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtmapmrweq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtliabqqjt.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtxztjapva.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtzgreiyxd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtrhfzrfaq.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtrgzpmhdj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmidhhnyv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtrrqfbmty.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtotliftei.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtjfdgglmz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtaeanfejw.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewvutjpl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtiqvriepc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtvhymqffl.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrzfibmf.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtgfudnomo.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsciqnohu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtcmlfuiaf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtdofkkfvw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gtjtcncdwu.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtjvkvsbsy.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gthuxokfpx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtjmuvymkb.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtalzvxbex.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtgovawdrw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtxiwhlczy.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gthejdcaau.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gthtxdyoab.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtkgfpskbx.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtuttmuvzh.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtlpmjzgul.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtvcqtpsij.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gtvezlomyq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gttitnbxdv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtksmifdzu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtabbvayrf.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtbizwbedx.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtahcawodc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtxawewdfy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtydadqfjw.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtafcujuvc.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gthsurbqmn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtbzknffrs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtymmapjvb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtzyzkzjsp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtwpvgerel.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtbigzjayi.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtlbscqxld.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtaxtwipbf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtoxovlqhs.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtqpmnbygj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtsrftjgch.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtawhvukkn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtfgdqmivl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtxoumgitw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gthbtizfvs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtotyfulzq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtevjbwdvx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtltfdtkzu.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtqarwheey.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtyrhspbtv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtnhfrbbow.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtukphpjzs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtxnsqzlhy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtfcojfllc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gthymlgwcw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtxqbrvwow.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtiutykkdy.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtrmolxksu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtoilaadly.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtbkdejjqp.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtmnclcvnh.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtbtyflocr.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtobgdmfym.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtxtdsqxdp.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtzimlnzfp.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtcphohncr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkhbyyqyv.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtifeaidro.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiondyvod.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gteiaxvrfj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbxsrswu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtbtqkpspx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtqfsetlrs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtzrcbmyph.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtchmizgyz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtqwkfyxly.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtdodgzwrh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtxhwosekp.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtlqzdkwuu.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtryjaypfu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtxmkofits.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtkulpeuua.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtxoyuqnlx.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtsvmdfdrp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtnjvasjth.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gthqjlxytp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtqbuxxzml.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtqnchkpum.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtsklrvhvv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtrxdjkmqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtunsazxdc.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtyjyuqmwu.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtlcsmfqya.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtxguztiyi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gtppewxxdh.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtcazcxjkw.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gttwkwxvdz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtbblopius.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gtrsdicyux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtejlwieuq.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtyzabkkbk.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtygdwwgic.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtqpxssmpy.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtmjqaelxz.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtgkumvoem.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtponnseqg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gteeizgaux.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtwzpwjnam.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtjfxqinvf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtnesrwuhp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtovivulbm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtlbufkjcy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtocflxhmd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtofrrmtan.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtcsdpaoyr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtxdahwyoh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtyhtefpsp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtnjqxztbq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtlesnyckk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtlchhqbrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtcfsvpjyh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtstglxkvu.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtfdkdiupz.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtczlbfoxo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtmqzbjowv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtxgpqflpn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtdahlxpvr.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtehjvisht.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtdewfokqk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtvhyypfiy.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtkqtlxqsx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gtvgqqkrko.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtejdxhfcw.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtuzdhvaaq.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gteiqqzzmm.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtykuonrmb.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtworgcdjk.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtyhiloiky.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtultkjpja.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtmtsfabdn.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtsjjddlye.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gtdldtiwyg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtbguslmqf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtfrstolfm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtxubwhyqr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtdluncojg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtjkwwsbuk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtkebniblk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtwsnzdnzj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtzeojukdn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtbsfjxqhj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtcepqfteu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtbaqefojb.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtxefxahyr.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtavbvbagk.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtskhfpump.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtjhdvxdak.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtfssolcvh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtxaqtmghs.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtbtcqcaen.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtociwarub.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtvhxujfvd.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxbqxin.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtggkyxodi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtpneildwa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gttpprwqsz.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtvaynaslr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtnfwdprzh.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjgmflaz.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtpykjbpbh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtzcamlsnq.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtrovecprz.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtakhdkrps.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtesvyxtuo.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtonxmvusd.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gteygleojx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtronnnmuo.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtemxoafll.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtmgufnatd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtfzvtzsuh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtjyijpvzj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtdvjudeaz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtefkxstoc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtbbcwuylw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtgcytzpuo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtvlfutbrf.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtlpvaibve.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtnepikxoz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtfflbwiyn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtfxeoaiar.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtsuauugvl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtmuyqzogd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkoqenba.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtopzciyrs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtejpetfcc.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtvuqnfkve.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtnsknfzct.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtrtwcmbab.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtywmdxhme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtfcxmcalc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtkpjefspd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtmaxhsbzy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtovwspcqe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtxrhzzcri.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtddcyflcg.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtnpxzifqd.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiqduxho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtjualloaf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgtnbqrg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtaqipekan.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtmwuhjlsi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtminrbwyf.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtxzyrller.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtpmuemprt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtqvgythpt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtbkguhyry.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtrlugmesk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtwttgudhu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtvdsxivhw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtnlfeoqip.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtrxjbexit.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtxuxftssf.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtwkfozwur.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtprztqnca.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtcufesfio.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtwunzvomk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtdtatidmj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtchjchrxe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtjqhqbczn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtyzchyxer.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtrxrozfeb.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtmsikduvt.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtbirddzhi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gttcmiiihd.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtgktlvugf.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtcuoadqbd.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtshdgmegb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtkuuwuohl.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtskikmmut.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gthcxzgfoe.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtwcxlpgju.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzkltnnm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtkmhjlzkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyisezisz.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqxsgmhuo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtqdpjclru.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtvsscivza.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtmiunonop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtaumvdgjz.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gthuzibsty.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtgguykkfz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtejivogdc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtkfemdhlk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtnmjjaqwp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtbsjhkzod.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtvaxsbdhu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtzuubzbgr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsfrllzxh.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtkoplvjyt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnsonesve.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtrqdufkja.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtuidmhoeb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtdkidscjk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtpwevyhtj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtxpqeyvrq.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtiixguf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtnmggpfoz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqnuogpp.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtbdqlmaaf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttkaiuubq.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gthlmmycwn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtrdhuxqab.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtakkgmsel.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhwdbtjl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtzfghwter.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtnbufmqdy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtvpmghfbs.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtbbiunpxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtzytybyef.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtpxmwqrrq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtmbgnorwd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtasxntfxq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxcnutqpz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtljndglry.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtmenbmhqx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtnfpwwozp.html


<!-- 参考信息 -->