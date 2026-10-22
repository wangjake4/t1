代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xrcvesvd.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2kidspcgx.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2mgaeuhsp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2omlecujy.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxcqceou.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2xlphewut.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gt2ocxwwrtf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gt2qbpcoyth.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2logdxyll.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2qjwwugfs.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gt2ottjnasv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2sifjgqug.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gt2adouozdp.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2mbshqxjd.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ighrchpw.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2cotsjuvg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egfedyrp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2dhhlvtkz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gt2zunfmnew.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gt2fhvlzujg.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2jnbotvma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gt2wydgzugt.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2zolaeqkf.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfybzlxo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2vmllmplv.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2uiudlmwe.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gt2bcxtxpvp.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2hctjujua.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2zmaegjlq.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2jcsprlqx.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nnjjtnbf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2qiditjau.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gt2ojntksdr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bchhslzc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gt2soepjrgc.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gt2mnqbimti.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gt2waybqmrm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2ebbkttyb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gt2bmbddxzo.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2jfmfxxfd.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2prcgvkcc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2kvsxslfq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gt2yhctoeee.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2nforffxa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eicnxzqm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2yyhgngjo.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2tidqevga.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2plrytuvl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwninui.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gt2sfbksdjh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2ulagtfro.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gt2dicpksjj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2xkhkmlsc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xserazmw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2jscejjbb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gt2mkslyual.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muurmzgk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2qiahmihf.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2ojaehuvz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gt2wiyfkqcv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2lyfqedqa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ohssipnh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ubdopvya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2urnydnmr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qajmilxg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2bstoyiuc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2mycizyne.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gt2nxfffqev.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2cledfvsc.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qifcwyld.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2wkspbmjr.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2eqyrxhyq.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2abygslrv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2xduwonhc.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2gltdnqnw.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jemniskc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vvmfklxb.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2niijdiwo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2fmbveome.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2arrvshza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gt2jdkwiogo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2ixuuugks.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2shjpaiwa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2vvlpruis.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2wvsslhwi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2obfitxyk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gt2yqhmfxhj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2ttosntqo.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gt2etybhuaw.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2vgyoyrcp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2ywqyfrxz.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2eovvleit.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2futwprlj.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2tatefbwu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2jsdrqzwz.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2ftudtrnv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gt2dxvkxris.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2mdvvviyc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gt2joimgkpd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2qaupkozs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2xvldleaa.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pockxzwo.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2dygbbtsv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2uyauoadi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2qrmxgnac.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gt2wkzmsrtc.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2dcypvdbl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2eqnysesh.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gt2nimdkfdn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gt2oypndayc.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2kyoeazwt.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zffwpbzz.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gt2vorwrcmf.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2rsdgecci.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2fwpknhqu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gt2pxfmexls.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyxdnjby.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2ywjspcmd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2psrwzsll.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2cpowilxt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfhwmkso.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2nghshpob.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2kstageoe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2rgmgawys.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2wlvjuxrs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2zcdaneqm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mghlhxvp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2qbrbieje.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2tkholykt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2mqhgxgdw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gt2plaoahaw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2fzwiyemg.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gt2bigmjmkb.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2olpnepyu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gt2iwzsbtfw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2zbsdgzew.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gt2peigkyuy.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gt2tucbjjzq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oimpgrym.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2fjkkmcta.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gt2pugzqgzw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aviwdyxw.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gt2zjkwqiuv.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2dntkuxio.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2yptqaaed.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqpwgjrd.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2oxrkqciu.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2vnyzrrot.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gt2srjyldcb.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2ovjtpjex.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2gbjjrril.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2yntwbjzx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gt2mtfglqau.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2nihegjrc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2dczrywzv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2eldhrjdv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2szphqqvn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwwanulj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gt2rixylmud.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2aixctsfr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2oeryormm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2zscyisow.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2ysudfaqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2krclfszy.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2vtruvkvb.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2qlalawqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2gevnwibz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2hxrceiko.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2zquckdpa.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gt2jymyeudn.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2ordygqap.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gt2phvkdrql.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2rtyszjtt.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2lkkphseg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2frhpgwdk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2bijanbyp.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnvvfsbu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2tzrtgvhg.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2plnxbvdu.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2coeqgdtc.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2yujvomul.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2mfcbolgw.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2kiiuetii.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2gaajsemo.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2mneilrdk.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2hlcxmbki.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gt2oocjkrhz.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gt2hljixall.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2iavvxidz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2hlspbjhp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltgbeuku.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2fkwccfhj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2ckiwtfry.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gt2xaayjxmc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gt2txgtugiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2mnkbsdvm.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2erjyhzcz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gt2zirmvkvh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2dbzpmbbz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggvnxbce.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gt2piwbjuhy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2raqmlfhb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2bgwebsmw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gt2bqhblvcp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2lmypystd.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gt2sisrxazv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ilnelmif.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2ogramhyc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gt2pttvxqfa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2nrlitsha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2kaoptklc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pypippwl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xvedbapo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2tqqxkeid.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2xfehoxnj.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gt2ingeatjo.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gt2nzfmsngn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzeyiddp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2eklcrciz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2sadmvtxf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gt2bbembhbz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rckdgcrv.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyqwlhcn.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gt2bfrzehdl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2bxsvldvh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gt2zsboglfw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2ugkidmgx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2evvydsbo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2ivztvcyu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gt2zoxkpmbe.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2jxhscpbn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skosichr.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2diggsuih.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhrannrd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnkcoqyl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2qkxgpxvd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2bvwuxtms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2hqchrqbh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2vizlbjtj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2vtidaezg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlloxcxg.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gt2rayshpyb.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2jjbnuuql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvdaqbzy.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2evbfitvx.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2zrweqxao.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krodnhsd.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2eclfcist.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2rhgdkvns.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gt2icohnwxw.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2rfsvpuau.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2egudqadx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2ucogluhv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2nnunpydk.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2pqhlnkst.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2ctegzpye.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2hyngimsh.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2zsnusnyn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gjzcpnie.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2tyxnnfad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2dgthgtqn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2xghzuyyt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2mciybgly.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2ygvfkeas.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2jaxrcrrk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gt2clvorona.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxqrzzjt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2xvdkqukl.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2fdtaylly.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nxbnqcwt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2aranopyg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2lqvpshzs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsuvceaa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2mvvinjxg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2wynklkbv.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2ddgtxmde.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2ewspxmzb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bitaimpi.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2molqzzck.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vfcvbnsc.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2cllhkcvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bghghwcx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2ialhmjtt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmyblsmm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aysdoqqu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mgpysatz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2arindmdp.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2elmtkpbo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2rcylsytb.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2rojrvsgx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2adbragsv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2nyjxpxmc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lzosvsfc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2fxlpshbh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2xnparxad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2kiqyvrve.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2opiqwzaj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2tptulzic.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbqpkdbq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gt2feptsmbs.html


<!-- 参考信息 -->