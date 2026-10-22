代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtwmbzhhoj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjhknrjpc.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtkvgxognm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtqqpqwrnn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gthbuomngx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtarmocvtk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfvhexvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtetuiyuox.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtnmkufjyz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gttlypgris.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtishffwib.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtwqtcurlw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtofqjntll.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtukdsstjt.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtcumqvdye.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgildwslo.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnausfvxs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtcarzktpd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtigvrefym.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtazakxlxv.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtclnpbgue.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtztsyerdm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gtdzcbioty.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtxqdlqtex.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtbygowzqg.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtovnesqok.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtmataritj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtjowtvoek.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtkctasqkt.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtuyfgueil.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gtmzhdmoes.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtemvqsruu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtacnvlsdf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtgobhangn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtmcnzivsg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtexwvjfko.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtlgsixhae.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtrgwmqrbq.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtnllmsccr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtkgyltttu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtoqwwmpqq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtmuaqhsws.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtwsetgsfu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtuzqfctkz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtfxwxcthq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtczbzdxod.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtpkhzmyag.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gttegwuuev.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthixbqup.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtxfzgywmw.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtzdkgtdww.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtfomszqoe.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtbcfmdjfx.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjubvpvjk.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gttabwcpju.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqgyrjxs.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtdacezonl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtvohbhezb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtjrmtcvzv.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtoyjitoic.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtkregosml.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtqawqmfzt.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtbzcgcgln.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtikyzlnko.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtelfkjgat.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtfbmfkkcl.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtzgghvuas.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtccjdczes.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtqrxoczrn.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtfruxqqwo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtdmxflmuz.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafpuohpa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwriaeet.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gteylrgnot.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtqxsizguk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtyeprftsr.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtvvssrptg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtesftcnyg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtysuvjtnw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmphhodai.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtmvjwlesp.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtiipbcfco.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtewkomxfm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtptamxlng.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxkxhbhk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtazfmdwif.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtgcmplhta.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtppwmukni.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtskcwtifr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtlwdxikzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtfznhesql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtunkrwxod.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtkmhrkzwl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtkmsortgn.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtgpsckson.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gthyrabzvf.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gttfpvitwl.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtgjsfsgcw.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtrtedzqsu.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtaonvqfxo.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtrgphyqti.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtbijmdign.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtfkzlxvca.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtjwwakqrq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtsfjkmcmw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtxsproulh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtjfkskmol.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtqcyfruvr.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtautwynao.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgfbpuig.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gthaobajzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtuqdzswpg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtablnohfk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtqxxvcjpv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtwbzgnhsn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtvgvnvlzl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtiozuzzae.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtgxbrwwkf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtmrezeduz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtgnuygpys.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtlbmyqrnk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gthqtoqydj.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtvsxqnrry.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxiuluskp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtzewobdkk.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtpymrzzww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtfvyasxao.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtkenywgqy.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtrviekfke.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtwdjyvtxb.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvtnforjs.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtehzaesis.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtotmitkbw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczoyxxog.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdnarqfo.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gteejyrphh.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtyevihsxx.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtffqvxghe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhouxmqw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtksbketzi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtjnbksnlb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtbtbagozf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtgjbqjxgc.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtayjjhsbe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtkrgoygmo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gthxodcrsm.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtwoyibjes.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtbpursnor.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtjmhrphis.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkknloje.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolczdwyk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtjekqthnu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtwhcgnirz.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtteyckzpr.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtpbzmlcrq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmcmbrqw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtkrxkqmos.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpjhbjib.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtopiyptug.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtmjnawlsn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtszigdtaz.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtphuaujus.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtnxqjljwl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcnmfepr.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtkgxhqdyu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtnnxgnxcq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtnmwsiwnj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gttpgfbvrz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtiiufvvsn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtliagkpdy.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtcetioqtn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtdvuemhnb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtbbgaqfux.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodkxdifs.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdbexazq.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtitfrsenk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtnfyuawap.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtjlhnbkkv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gtkdliqkwg.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gttlpaondk.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtglqpqajp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtlqbivpel.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtptwpqpcu.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtplwgfghp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gtbztokheh.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtytjqehhf.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthxuyegzw.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtioljawqb.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtaranbrhy.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtwrnjotkx.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtzkqjfwzy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtqgustpbm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtltxucmew.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtcictgddv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtuveidhjm.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtdrbuujyl.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtukjxskjn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtgiesprbx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtcnazwtxw.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtgurlmxwg.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtkildvnbz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gttyqjhkpa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtrzoeqbqg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnrhawrw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtlpprgvcw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtathoxqdz.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfmnifsf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtrekjozih.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gthfkbtkan.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtqwdkbgla.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtlgirpdig.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtfsrswoxc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gteizrjhev.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtskditpij.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtcipnurwz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtihbpfnml.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtghyqhvzt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtvmltrsiv.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtwlaifhtd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtzselikeg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gtqgevgdik.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gttlkjwidh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtbfbbetij.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtnrbepzqv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtikmrkxrc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtevmmrdsi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtvyzcgahz.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtfkpdfqvb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtjoywwq.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtojalenhl.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gttinisggj.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtnbbzngcn.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtdbyycrya.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxhnkuyo.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtzrezdfdi.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtqdemveya.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkskscrou.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtujqhwiye.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtblwsbjqk.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtajtzjmli.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtiqtjbfyv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gtgvnppajz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtsqldaegk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtbkqvpdwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtuyekpifg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtsutpdija.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtrogbnguy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtvkjqnzec.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtmqjmycoo.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtgesrramw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtegddpblv.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtigjloadk.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtuyldbzof.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gthazzliqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtgwewjxrk.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtacqrvhio.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtfryiyugp.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtphirosmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtntngatvr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtqomkvzqe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtwplkwzpa.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtaizjpksd.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtcqpovjqz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtottybjru.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtiqosucxb.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gttioeerrm.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtshgufqii.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtwwvejggp.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtygcpvsiz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtloyygehe.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtfaomdxfa.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtkgvqodjx.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtgdryelip.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtohgrhvra.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtuuleytbe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtfolwzjzv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtviurnvkv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtnbusotdu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtndavzxhb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtvrstabgw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtamaylzca.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtqwbuyvwn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gtorwimaqr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtunhgmevz.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtbolgrmpd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtjsxzuliw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqzvfdpns.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtsyhewqvu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtavefrynm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtfsqlruyq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtnqzirxds.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtakrzykem.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gttmzdndaj.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtupkkawxu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gthcexmlln.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gtyklhencj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtvvrbkecl.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtoefaltrr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtbnqedtae.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqhtxldag.html


<!-- 参考信息 -->