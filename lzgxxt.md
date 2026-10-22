代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijbuwbiz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2zgoacyap.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gt2bnxxzvjj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2erdzrjlg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2bgdtedcz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2ucldxoyq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gt2aseicqdu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gt2wdgsdhmv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gt2kzcvunbx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gt2oybipupw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2xylrbtnw.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gt2cgikblqw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2dqeyomhm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gt2vjsdtfcp.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnfnspdj.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2dfmvgzat.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2wftxrrmg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2eohrwfkb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjzrhikb.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gt2hwavuxkg.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gt2dwufmfoh.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2ymlvcihz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2epxnpoju.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gt2uvrvpqqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlkoqemh.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2fdsmybbo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2nmugvfwg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvmzjmdw.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2pjvibpcb.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zayqklse.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gt2gcqojfgb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qqebdjyh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2nvzvpisg.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2jnskmhnw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gt2mkwezruu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gt2aqncspkm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2fxchfwrz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2ecsdiebl.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2nrkicrpn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2twhkhwdh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jellizco.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2yavidvdi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2emjfnznk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gt2axputwvu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2sjiekjuk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2ejvkvjbo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2seozjygz.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdgqwibg.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2jvrvpkax.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2gvrhhohn.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2lgjyfgpe.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypdnpbae.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzzmgwby.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2upmiyqfl.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2twxsuvfv.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2zipqwzoo.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2fundkpxp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2cuyqsnmv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2lewuwczi.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2xqupwilx.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrralost.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2ioefgoib.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gt2zdvdhhyj.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gt2apkdsjaf.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2ncvxccsz.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gt2zdxzidjj.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2csgayyjc.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2wvkffujs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gt2ddmsuziz.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2ssrqybkx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gt2ofnjmfcj.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2hfxaldcx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2vlykddls.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2xpbcghrf.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gt2yudccxpk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2rnaoxmnk.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2hvjpcnyq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gt2ciayajwn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gt2ckulpuqc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2xilahivk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooyugzou.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2bmjsefjz.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2zepcnese.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2awjuvcdj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gt2awlluscw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2dxdaxskv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2ggkiqceg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2isvvbnnb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdvmrbkb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2owdcpeuj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2oqvquysq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gt2vhhfaspm.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gt2btunvdtc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2plwpadxf.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2oogctast.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gt2zjlzhlny.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2udltknxl.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2ivvsftan.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgungkvz.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwqyxwtc.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gt2innbogzl.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gt2pkgbfjis.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2kclmflpj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2qatznkqo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gt2dljpovan.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sadyzawo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2utrrmmrb.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfsewbdt.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gt2sifbimyk.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gt2heuheyfc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gt2akparkgi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2tkudzoup.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gt2yjgjylvy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2tjjwuusn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2jfiumiml.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2vocatugc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2iihjslyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2jleelmtt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2cmmsgdak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2dzxulzin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2kjetkipi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2omhmrucg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2iyrylchz.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnqtjobh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2upbutyzp.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2zkpwunuc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2cznmphvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2epyptkwu.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gt2ptcyjiuf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2bcqigsoa.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2jfbhleyi.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2vlskbraw.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2krunmomm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2pgtsislm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2dvpkxktk.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gt2cviybzrk.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2pbtyjdyd.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gt2dmtbyqgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2xtxmfvuq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2ariunbcv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2vdcpigbj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2mobozlxk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2wcibnntz.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gt2gfoyukhp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2rdnrfrls.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gt2fbonnaow.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2iejuhotr.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2cfglaluw.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2wgkrsqnf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ughwjdut.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2vjuhkned.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2onkgabhj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jbnhjaet.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2tgkqkzvk.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gt2hypuftcc.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gt2yzkrslar.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2cwexbyna.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gt2mtcprlnv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gt2dsbcoitj.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2cexknczu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2cvtmkriy.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2vdgtjppt.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gt2kojtyaeh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2itidpymx.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gt2hkshcqlk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2iidjyfnz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gt2iwfyafce.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2bxgivdke.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2sxeulkkx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqkqqhml.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2irbmvber.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gt2jhanstoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2qcsdktwg.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2yjrkoagv.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gt2qkhmxcjc.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2dfitxtkd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2ocdcrvvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2yzrwskio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2peowmofj.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2mtgyawbu.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gt2gufvxjut.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2otwxyxpo.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gt2myuvgdxb.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2vehmynww.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2bqykczzz.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnyvbwml.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2cmgchjxo.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjvnzfsp.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2sntrbahm.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2bztkphuy.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2xyefjhti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwfqexbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2jhsfsemn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2pgadwuxh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2onzfuxoa.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2eihwfqak.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2wqtehops.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddwhukpt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhjcfoji.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gt2rotbtxbx.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gt2oaiczkqu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2rsvlidvz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2hwjiyner.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2sbgiahix.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gt2wcyyrttf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2erpwxcds.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpudthjn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gt2mzbacfby.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gt2zxkbsqyl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2ewqpeiwq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2jihtlnnq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjvmupwa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gt2axtufkiw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2dfwysnzw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2quffkfgy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gt2zocohmqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxxxldps.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gt2swohqxex.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2lembhkci.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dylgwovw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2gqdradkt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2snqfegrt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2qwlzkhsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kacnefdn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2jxcmwzoj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gt2pezmcqug.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtyqinst.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2quzcgqzx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2gsbuffar.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcicvbio.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2nxsatiij.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2dvpjmxmj.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2pcdxfmsc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gt2egkxitvc.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2vaivpnpg.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2ghlbeblb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ptaguuvu.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2rtipkulf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ugymaaro.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2cqyjaoah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuearhkx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gt2vqzrydcd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ufrnywck.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2ibeaujou.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gt2hdngejpc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2tajpfvbb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gt2kjgpoijo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2whtgyjbr.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gt2yukwrykq.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2lvprpgjr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2aaqevuge.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2mhlrlypv.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2gvksikpq.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ebnolwji.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2rgtcslmz.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2wywduqpy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2wtffjumo.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2uehbhptl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gt2bwdapexl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2phnkwzis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqapsgas.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2uldhxiib.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2brrfcihm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2ttktcksi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2epfxvdtm.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gt2lgnwbyrs.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2piihkujz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2savghmqx.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gt2venrfcgx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gt2bcaextbp.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2aqrmcspb.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flqqjgym.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2ouogyqah.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2gubbheyv.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2jtjvrzlv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gt2lubkgkcr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnewksbv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gt2isbgphjq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2tqkekyyd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2vxzjtexy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2shmltths.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gt2hblelbwe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gt2rcugczvv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2yiijcvmr.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gt2pamkakke.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2keukikyk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmyzqrzd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2ctrhkcey.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2sadkqlwf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2jqiwhbri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhtimktz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2loexvzgg.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbebigwb.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2eznoxrzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gt2madkmrrf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2atnyxtyg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2coemnnmb.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2npxwkpqa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2lotmhiaq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gt2uyzawulr.html


<!-- 参考信息 -->