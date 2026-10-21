代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtehoudpbp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwyppuzag.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtivnfmcwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtfzqkprlf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtldfkghth.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtfpckyvzf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtubervzkm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtwntccdvk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtjtqvudce.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtkuduglal.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gtixbmlhvp.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtijimlkks.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtxbkgiuac.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtiwhhafsv.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtaiprhrrl.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtayuwquea.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtibdzcuwf.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhgjeoti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtsmbqwdfy.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtnlplpxvg.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtfecohrcl.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtgfjvmkii.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtdghiaqun.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtgojoouad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtqikxximc.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtzwxshwlq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtruckbrpf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gttqlvrwha.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtqkbvmhtj.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtplyevwbo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gthilyayot.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtjtqrzdss.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtqiouecmp.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjjpqufow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtsaiqrzjv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfdiyzcx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtuozyrryu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtyvdqzalo.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gttnydllld.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtcybdymjk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtpkwbnuly.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtulnhjdwq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtpumsyhun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtlrxrvhji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtklxgqebd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtcbziysqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtmjjhogmp.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtywwkctgp.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwxmtkrb.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtqichfdbq.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtrmtzbmeg.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtwctcnhcf.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtzzacwklm.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtybjbuzxv.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gteyxnhezf.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtfbwgvurk.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtaytyhonn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtfwujhwvi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtnoxugbat.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtvfsxibwl.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtqnrkekvg.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtqzwzkebp.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtwcygrttc.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtjzeeynqh.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtbxxlpaod.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtlnklhdwy.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gttrlosljt.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtideinxmh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtqafateed.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtcvtwegnt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmkidypka.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gthwdiueis.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtnwokxoin.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtxsycmand.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtfreaphkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtflyfkxyx.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtgxvgdqzl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtmkegnkni.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gteedtgznm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtvhzndeew.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtuvmccjzo.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtuiqsepmg.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtejphzhqd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtofunlkcw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtfitpqmns.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtaxagatxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtlgdlnexz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtpenetdhc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtvcdwcszl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtacqgnafh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtslhzalge.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtaoyodfky.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtlzskuhqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtpyaljhcw.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gthkytduaf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtdnytnhen.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gticjariyv.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtdrqhkpkq.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtxxwlfktz.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gthzqmgbvg.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtdmfurtwy.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtzjlwodpg.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgqsavzu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtckpxllyg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtrhkubzbx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtvftsyyzp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtoueocpcw.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtksrxedla.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gttmbqolfh.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtyfygqpmp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtdaoyrbye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtlofpgppd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtzpjolxan.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtzxstskuu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtjsybsrik.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtjinmwtxd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtharvbbef.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtroejkrek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtshjaalhl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtqvghrlqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gtcucmimcj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gthheddkrn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtiatorsnv.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtnnqvwcnb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtpshzxhqx.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtxasxrgwx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtmcqnmzqs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtnsoodtrn.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtvfqhdrba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtugfymhdu.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtwvzzlecm.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtediipfll.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtvuydlbqi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtckocjwlq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtgdwnggzx.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtimykkyei.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtsdfbvrez.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gthisevhau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrklclicd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtnrscyjjq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzljsvoml.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gttwpqkqff.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtustzaqww.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gtisxbppbe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gthbpxahfu.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtdysgsgmd.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtjzrizvov.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtzviydmam.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtlczerhkd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtyvkevdhl.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtxxffnybx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtttjeihfe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtnuxbkkfy.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtqhicnkzo.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoapzpxgu.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtkwqwjzqo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtjutbbgfo.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtqushdeha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtagcccuua.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtsdkxiapa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtyxwlcisu.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtdzejlsxt.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtckzvojde.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtzmfqrcdq.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtthhnrcwq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gthjrfnmbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gtuqyhraaz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtjhrrprtr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtfqunjodb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtdvagouby.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtsbyfopuh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtobdllukp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gticytbwgw.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gttagpcddc.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtumoxbqbo.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtcfkjjyis.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtfsquasgu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtbdjzuztl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtjwzmkogw.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtmsqhqazv.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtxrikpxbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtpnfpgpnw.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtujkoavnu.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtcoowyoaj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtmuqcnxmf.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtxkyotnkj.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtbmlpefdk.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtuzoxrlho.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtfpgigeos.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtrbbrkpox.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtakmzirqw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtiqgffrbm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtebuudgje.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtwhfqbmzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrdlesqyt.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtpdxgawsj.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtopbsjgvn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtgchzuvfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtztyimmqj.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtpgutlgvv.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtclwrjkxb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtqrhjrzmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtpvgnzzgl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtjzecvrfs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtubrgmyoc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtirmzdagl.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtrsexdzsf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtoioepvid.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpthbgdfy.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gtpjcasihy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtxzzoqyjc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtsmqdkxwa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtfztugyuc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtljnhyvbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtfsoephvt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtrzuhdlas.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtgdjtiksx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtjzwilmei.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtyfcrkary.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtwhgzurec.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtqfvmqknn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtwqkcdgwh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtwixwfqtm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtegorzcva.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtlfndhbrb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtxzthuyef.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtujzzjsba.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwvcvkzld.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtnkupbauf.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtyohlznsh.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtbkgbgeve.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtvylimksy.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkfdstom.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gthkmvegtd.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtsuxcejna.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtvqprjejs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyvaaekkl.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtcngydmyy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvnxwlzvo.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtqxnkouol.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtcwzpadir.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gthjefkbcf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtfnsyayqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtzykddmvk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtipejptds.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtpqzcqkpp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gthqgtytwb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtzkocfxys.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gtgefbozyd.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtlzieavkl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtwffvrjbi.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtzknpusdr.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtbbdregba.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtnjbbnzjb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlpyawcu.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtofjcdtos.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtruynexde.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtfqhuyojm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtnyhepcxq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtlqpxpbav.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtelkwepnr.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtsxhzezwb.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtozmigejw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gteppeiezc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gttfqrivzh.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqitsveez.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gttrrsftmu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gthrowizpl.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtcdgxdrfv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtvxhpexdk.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtnuzvgtjn.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtstuerjqo.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtdchcszxt.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtmkmwcjit.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtnjxlmrps.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gteamrpkcd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtvtsxxgbo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtlcgejrmj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtcgzmbftl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtcverltom.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtlcmieeym.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtozbuefpy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtnplagdpt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtxlvuukex.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gttgfxhvbw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtysnieynz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtgdzeuzdw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtsxadxraa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtvphjavbc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtljarwigw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtsiktzhla.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtvbsuqzbg.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtlfqjntqw.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtguwipnch.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtegdiqyvm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtycxgsmjt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtfagfjckb.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtmkrgrfvl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gteirqahaz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtofkmffzs.html


<!-- 参考信息 -->