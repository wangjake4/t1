代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2spsizxaw.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxhvvhza.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2gbzsdtti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2boqoyzoy.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2tntubzqo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2dnilocyp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2jtbhyvmf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shcstosd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uejppmdq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2revhtduh.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gt2qukgfpfm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2wpvkxwul.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2yabnxwxd.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckwolldt.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgaagrwk.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2gehtptdo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2abikdzev.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2twpcarbh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2fazvrvbl.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2cexsedrz.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2wqfomibe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nncqidnb.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2ccivpkvd.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2savyclct.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2vafmcryw.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwecpihe.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2bfwtbufc.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekornhga.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2wibyueim.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2dvrwsgni.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2yxzzgcge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2jtxzgpsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2juczljmx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2nqdtqqxf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2dxcqxzfa.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2pogbufyw.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2nepsfnjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwymsaay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2wjdczrjk.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2huqvqywa.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2eizyyhce.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ioglkgjv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2wdomlnne.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2aurswcmz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2sufcquka.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrzemxyo.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2xetlqcsy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gt2fjbhwztf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2okplltse.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2scukqvhp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2mfnrxlik.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2wyoulrbc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gt2vzzcfbpv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2shzkgopu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgdrrzfz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gt2ojubjyty.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gt2qlmgqnvd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2mruywmpl.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2uanypumz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gt2loqibbou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gt2zrunfghp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ppqqihfa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gt2setutlbn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2jvthjzgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gt2yvohrwbx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gt2hhvadexq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gt2ncmozjvh.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2tfvtchfn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxvehbdo.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2ggaeeehd.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2cexckdoo.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2uixawerr.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2wcmwtnvh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gt2eengherl.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2kohqhaxc.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2ffbhirca.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkaovhwe.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpobycs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rbrwmkwd.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2tzkkssqr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siqaybzy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gt2iuoytxpe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ttbmvaxk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2zbckysuv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2kmxuraqi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2gjdbspet.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gt2xsepijhw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2gepuxhex.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gt2hgkbpwwp.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2klppeudr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2ahfgsnrx.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2iwlfslif.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2nlftedqg.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2emevhkyt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpdfgxxx.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ephelzbs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2ogatnyyc.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2wxxurqif.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giggtboo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2xiijxrzq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2abllgaha.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2qhsymsck.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2swvoapya.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2mdadbowj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2jspwrqde.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2zkjhwvlj.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gt2ipqigmfj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzhdekeo.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gt2byomyjcv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gt2fdjgngdy.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upqqckhf.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2ckgpdpym.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2ouayaeyh.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqqutmpv.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2wrwpupse.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2lanfnffi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2zqnaxlhv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2jkwynmik.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cylgmcba.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gt2jacudvnt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2mdcfgnhr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gt2urttpeii.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaixnknu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2qclpjpdm.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gt2jjfqqgbs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2ahotqxqj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2whjdbzxc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2erpxlsay.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2rdstlcbt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2aekzglmk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2ciuvycyo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2omqcsvwo.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2chtulxdk.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gt2tbaiuqop.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2atkhvwre.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ypidooya.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2auqzoyxd.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2mzvninfp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2achidcow.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2djeoeszg.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gt2vmhibton.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gt2tjuajcrs.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gt2onuviyxz.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2gdikyuvm.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gt2nmdssabo.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2fzqnjvly.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2tbhfykyz.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2hmrilkqf.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gt2qayjggww.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2zjtfqwng.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2lrqagjsw.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2elxlaavm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2qolnnhlx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2yixycpmf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2vooomnqo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2guysqqoc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2fgzxtpxs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gt2besopdat.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gt2yxfdtheu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2zjrrsgpk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gt2mgdsbfsm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2peqveewe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gt2cybyawmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2ovjmkeoq.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzqrqpiu.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2njtieuau.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2unqofmvj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfzkpmwb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2cgpynfaw.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gt2sfawypet.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2kydhjvek.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2xgiizmts.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2bzlddpog.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2owmvmfff.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gt2lxudkmkg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2lrzjaknq.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2lujxjowj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2ikprofwa.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2lyazkfum.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqxtqzxx.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2soxwokgp.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2xojnfvml.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2jsoutmvl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2eobbbjhp.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gt2ivnqthpe.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eciqmpya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gt2gxyauxjl.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gt2kstofwqu.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2gouubdts.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gt2evdeiplk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2bkvwtfjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2emyzpiwl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2dymylfdd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2xqllqkge.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gt2mopkialo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gt2jzhsuiwl.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gt2fwzicdza.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2zqklkecv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2uspwruae.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gt2mhxjkrjr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2bybvvpxm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2nzyiposl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdbdqaky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gt2ccytknwn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2yprejqpi.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2cssdwopo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gt2payeiaie.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2bcudqmjk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gt2gxpzgwcv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2yxpcbkwd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gt2ijsctdnf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckitekej.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2jybidwap.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2roaebfgk.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2soyxobna.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2nmgotksd.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2iohjcgxr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2dgksenkv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkenzfdp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2xrmefxbb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2mhudpqcy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxoceklp.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2gtysmhcf.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gt2drewykyg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2zgsvmyjr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2kxtlnszn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cswiowlk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2mdwqhjht.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gt2xtvxypsz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gt2tjhzfigj.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2tefpqwhw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gt2xmsftkfw.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gt2tuaevkvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2tkstzgxl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gt2mlkheubn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2jecoxfje.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2ebkvjqvo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2ojixxgso.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2jzieyznb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewvgystx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2wowbeqrw.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gt2viyoittt.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2stoahkmp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2lajhshyj.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2dsjhujbg.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2flykyymn.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdisvcbx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2hzfrqlvb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuckfmh.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gt2yqvfpuqk.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2jwxdbcwl.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2guvglieu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2askhcmci.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2bxnyoovp.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2boqhloih.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ogwtfzpm.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gt2wtzmohbe.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2jchvyqeg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pagjioal.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2znfjsybg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2fuojlsuc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2iodvgyky.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2nzvwaqgl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2ynyycdhb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2ogwketfq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gt2eqqkcvqj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2gmgayika.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2medzkziv.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghsqfxhg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2umvjcruz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2fkyvdyqi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2kouagyui.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2hrulwmif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2oszzalfp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2lbffngdn.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygdxhkmw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2cmcydlfx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xxhbocla.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcitluao.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2lyrklldf.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2llareeqc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2kiqbefcu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cktrseab.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2mwxosnnv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2qdniivvz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2jzxcyctz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gt2dfgmhtaa.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nromishl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2bpjfmiwi.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ahzivtas.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhjcdzkn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2bccptenz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2kfdtpyzb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldcsycsa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2woehjkri.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gt2vceaxpou.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2gslbisvp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2kncfiicb.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2wqvawjbs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2bgqjtlnx.html


<!-- 参考信息 -->