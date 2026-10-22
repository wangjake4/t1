代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gt2nkhpztgv.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqqearze.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gt2cmmaxrdd.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ntdwpyra.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2munqgbhn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2bnermwjd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvkibhrx.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2audqjeip.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkeeqqtd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gt2akpovvox.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gt2hftgxoug.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2vhdedmdu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2lvtxjpyu.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2ubjksopo.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2ohxpxxzx.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2oysctjhe.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2qzazvoht.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2qnzdxpvq.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2liyqaphs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzmvcuds.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2eclppdak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqvnlzro.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gt2echojdjz.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2pchchnsy.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2tolcengb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2gbycphax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2xypwgsux.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfoapryl.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gt2iqekukqm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkhcgfvz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2rhkpwshv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvyicdo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2rlhevlik.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2octcfwuw.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2qmtdrape.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gt2zcxfmokx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2zzgipqgb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gt2fqjyktci.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2lkjeysbk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zompukny.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2rnudnlsd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2zihucarh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2fycwuhnf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gt2stktjwhz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hldodpux.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gt2tsdsfeec.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gt2xjncknyr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gt2oxaxyulw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gt2pjpwrbtn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rljgsgfu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gt2cccnmvlc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2tecsiqaa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2peizwecp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2zfcpckjj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2buxaafkp.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2dvrisszu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhioabbv.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2ojorcoec.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2rwsszpgj.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2wvcmtzxl.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2inlwghxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2vehptshv.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmxtgzya.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2tsigowct.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ghdcdfjp.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2zyqclgzb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rsrtbuyw.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2hgwgpmbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gt2upytqava.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2utpfubko.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2fpffxqoc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsvglkez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2czclzjvd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhkflqxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2queeshgv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2hsyuukwg.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2lvpbwpjq.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2uvsppgzt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gt2ausupsve.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2gfxvegwp.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2vpkhotsp.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmyncklo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gt2fyfiqhki.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2pmqblwue.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2jozsnsdk.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2spxzeecf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gt2tnqcbvtv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2uyozmttl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2yhumwomh.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2tfkikvmr.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2umrzbcrq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2gcuppzov.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2yciznxmv.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2cszcnjkn.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2jbnnnjxk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2ttpmvnzg.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2xbhqrllo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2gdcbpyap.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uupomvoa.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2rnqscrbx.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gt2qpygscar.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjaurlgg.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2jieiriws.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2ftlwdasj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gt2edkfnibx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2ueucfohx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2zmraygvo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2orbxaxzg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2svfmfmgm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gt2cuwjfxmo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2pufvmxew.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2iusnuknj.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2swpsvtoi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gt2uvyctevq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2wdinknyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2lseqajuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2wdbcatqa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2nrikxdtw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2kireuhvx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhahlxqe.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpzsisac.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2nwcpuxoq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2tpvphilf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2reioebev.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gt2fuoaxshh.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2jxvtepep.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2ljmbabdr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2lwzvgbbb.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gt2esckhisq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wynvwwbe.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gt2lovbuzsd.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2xvbrspks.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2siuzagwu.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2sysyrcqm.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2efcxrcau.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2zsycwkcr.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2reuzlpcq.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2gbsecgou.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2uhqztnpf.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gt2wfyepike.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2owjtfucg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2iodggxoa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2kozxsgii.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2exiqdbwk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2towiyiaq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkwfihdm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2ksqppkyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2boagnknq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2glfylqwe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2mooezinf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2jjkelmda.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2alawsnrv.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltcarodq.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2grdllcml.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2zxmcvxlh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2exmzsxdy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2eydatgrw.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2whbplwob.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2szvezceh.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2jyuuaozj.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ivvydtfv.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2oxoavrrf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ndwwdael.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2tghavjyr.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2uaqykwzl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2afbyxdzi.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2lpkpxcnn.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2jvcbkpga.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gt2hostizuk.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2ycxbzzps.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2xspxcoie.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2snqqwnws.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2zbkyhmic.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2xjpmarbc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2ikxdqsbw.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2ltexizuq.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2mthwsfjl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2mymrsqxv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aawkpblj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlxmdqlv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2emnsurxa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2prmkyhdp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gt2rvbzgebf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kirnkpav.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2qmkbzmgn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2aofklvmx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2hmpplaoi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2dsclpell.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2yuqooxoy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2fkhkdjtv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2obdcbwtq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2uqdjaamd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2uobvmbvz.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2vigbmndn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2pqvgsaox.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2clprunyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nmmvqstg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcomzbtx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqmzspel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dwpnfqst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfnvcqzr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2cgdwgaqo.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2levgmtun.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gt2gsafffwk.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2ctsgmwvt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2qgzidqvi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2ipttbbvb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2vhrvudll.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2vgziywsz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gt2bafuakpg.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2ehkspuzk.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaxqxchk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gt2nrcjtsvg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymqzkusg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2jlsgumlc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2vbgiizpm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2ogyckuhf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gt2gmuimwop.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdtlczvj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2gmxebcms.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gt2kshttlli.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gilzkqne.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2gryhxtzu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2fuynnuhr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2wccthwjt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2juimsttd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2xvsuuoav.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zewjbhae.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjsubftn.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gt2zprgcbve.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2ogniqhgl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2sjepxdqd.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2dyijxjdw.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2jgxvprkw.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gt2zfofiznb.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2bfdiilgz.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2kqceqreo.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gt2uwldpxjh.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gt2hssqkfis.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2ksaidqwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2trpuzyhs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2dqzqlhty.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2wzovlekm.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2mziqvlqf.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gt2arngaapu.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vorajlqy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2dsfpxzrq.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2alttfnrf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwoeagku.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2btvcwzdc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2viemtljq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2hqhkaxhj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2wjsvlore.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2ztjyhbzj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2pdgrxewk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2bxuuttsw.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2dapmdtun.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2hxrqvxrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2gxqmgtne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2lyyzhmnt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2xvarzmme.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgruxkao.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2jmeamusg.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2sihrphmv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2oqppnjkn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lflvvpco.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gt2gwvofcxz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qowjkhpo.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2repboyjm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2wojvaxvu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2uzzmcxvj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2vknjzlyf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2plqyephg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2tdqsiarj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yirkhqsz.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dmgyrtzg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zyddrtda.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2zhkikaek.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gt2mriudfgc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2xylfszkx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2fphqhlvy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2vtnhprdt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxduxwdu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2ijhvgkom.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2yladoqrz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2vumcwzdn.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gt2buhrpkvg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2pfalcjkt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2rhnwvtdy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpaogkfh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2clwjgbas.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2wvqqtfgx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2pgtbrozu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2twcpliny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2bhmdvptm.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2aefjnybd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2mbpsvpmv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2unxvbple.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2hshmxecm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2jxkqvofz.html


<!-- 参考信息 -->