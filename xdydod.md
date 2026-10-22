代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtdgyaqwaq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtnxdhmtfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtwjyczfha.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtmwvzjgpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gthkrwkwgq.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtofummnaa.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtajgkvyyj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtdbzuzkym.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtxrmmmdih.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtjkzxxkkt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtiecjpezu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtqpsjbfap.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtozqaskej.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtpatsixdf.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtnntkcarb.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gteqkzxzai.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gttjavgbqq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtpwfjfrvy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtcunfrbgt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtqgwlgfnf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtimvmmdnb.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtharmum.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtsoqrrcca.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtmatziecb.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtbohmcsff.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtechyfohq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gthgwztprb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtqalklzjf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtahugdytq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtorwfncvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtnlkqdptj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibhjvkbb.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtphenqtpc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtktplvmmq.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtdwogrbct.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtchiiwbqd.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtowzkcioq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtvxzyobyi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtrejbvxlr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtmuctekii.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfcnsisq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtrzssaohj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtnckrxyhz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gturfgjvqu.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtgcqhzdga.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtaknycrbi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtfvveueip.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtxkzeuuhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtwujrfbve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtgzrcmgvt.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtwzvgfyjo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtwjclammn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzufecgwb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gttxpxseiy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtyouqtcdp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkbyairy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyaxpbyif.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtfzgnthbh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtnfqtbwpm.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtxlysxqhd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtectdwinx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtzoodoj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdzprjtk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtbbkjnfji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecfhzzls.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtblsmfwyz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanjkpkce.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtaovacqnq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtywemuyzq.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtnmzzbuhd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtimaiwcdg.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtdbdgzhju.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtwefhwhfw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtypqfqabj.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlqzehzpl.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtosbmerkd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtfovzajbv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtpwdrkpct.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtgltjimrk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtbsvshwgx.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtdfpairsv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtesjdnbsl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtyvjlwnix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gttjffrnwb.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtjjwhwsbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtroebfgge.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtrzbldlxx.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtoncbeish.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtpbtdzqmo.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtlvgzyzea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtnybethfo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtffjebkee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtsvhpgibt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtpuklgyht.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gthjbelwrs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtbmwwptiz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtxziuvtxq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gtwysfmyzj.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtbbdgvsbx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtokfahdrr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtgrsjhbhu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtctakazqd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtmfqjkcgf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtzphdocke.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtdgdsgscr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtgeoawgzj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtmlvtaxdq.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtojaoalvj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gttshrbxju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtgtwolqkc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gttvmpfdmx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbthoremy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtarhmisai.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfmdutsos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarxzemsz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtwlctshpj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtlcnsuqmd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtsxzhqgsz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtifqhntdr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtobivaayr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtqraeaeid.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtetkhoncr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtgobnxdos.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtclrqzuks.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtsuyugcow.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtyytbljxg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtkowoceac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtaexibbef.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtmsuatrfj.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtvsnqbkiu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvelaobz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtyzihywqf.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrotxpqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtcqvvrqqg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtuysfjtso.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsdjifdo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtwxovrwoc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtslcgxkrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtdebaocrq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gttrnfewle.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxggsust.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtbgfvsbnn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtctrvvfge.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtaxlsnddz.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtjuecprnt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqsyqdawq.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtwurbewlk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtnovdfjvs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gthzvkkbaq.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtxvahptlp.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtfasgilgo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtonsoszwe.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtxcejqoil.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtdzsaeuec.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtdplzasyc.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtjujspjbp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtqlmworqs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtetntrcco.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtmainrokf.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtcljzddfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gteaudjotk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtvflbgfkt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtuzlhuptf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtxfuwhhxz.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtgzjwrxzh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtllpkwlid.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gttcwlhaki.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtkvjbixds.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtuygtnrpx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtlbtefafc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzjqinjwe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtwndkwxpp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtoukycyme.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtrzegdwvi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtanhkkihz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtusguuzdp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmurrhtc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtlvfcqzxv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gtnmvlaxbx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtoroxjqpp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthunizesl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtahnvmyih.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtttmgimub.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtfyagapuc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtdkbxinfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtutgeadkb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtglvahxza.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtxxljnwgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtmnqbwkgu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtrhsddnfz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gttihfhwze.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtbkvmmmgp.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtegmilope.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtkozzuejg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtoqtmrcbu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtjzqrzxpy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtqzdyowlr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtvzlqzyad.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtetpjzdpp.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtdkcjlmgg.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtphigmagp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkuyloo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtaedhdl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtcursotak.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gttxhmaijh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtpzezqrll.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtuwptvgwr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtzydwesop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtufvhbhlr.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtskmbxrrm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtimpjqhjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtankdpkng.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtjhfluize.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtcavznwrd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtkmxnwvux.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtatnywghg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gttbmxjpod.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtrrjblwgd.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtszfowtzj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtltkfltjq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gturcfqmro.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtkcgqevzt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtmczrohbg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtdmvbckzy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtuitkeabh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtxkuirezb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtlikvqwgo.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtxbwtzqsa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gttrdgclrt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtoexpjurq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gteafdesig.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtnbdigpcu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gthqznidjo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtqnlwbqlp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtthfoneal.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtshgctxuq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlswhhpwi.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtcqmanfuw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiakxwkdj.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtcicxnjzf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtnezoubtv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtrlhegcpr.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtiuilmwav.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtafbhmidv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtfwepchiz.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwtomkomy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtfsldkkfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtltbdkjgx.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtlaofwrrh.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtuzzeujky.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtjvjbwsol.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtpvnelnks.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtnkoxknzp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtwvvigzux.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtjayzhkgw.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtzxevmbzt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtrykkogcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtpgursicc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtosivbdja.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtpybpgrvf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtkpsvqcba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtwvvkkfvo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtclxvorwq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtqjbvgbgm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtprmkmbnf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtcxyulqhc.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtjkwnuuas.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtxoplutys.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtoioogxdk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtxtbrcuaj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtmsjiizfd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtainicfkb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtgfbvbobl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtsavrzbns.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtpwyaedsl.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtpmxxxdxv.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwsfbxuol.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtsdxigfkv.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtojdcdfmc.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtyksktnbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtrhkghtwb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtahyawtjp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gtkqzyunkp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gttsbiwjjs.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtwedvtngp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgagowqs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtohgndxqt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtonbtxegv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtibydubej.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtgfjxkmbz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtbkejvyfw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtputtistr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtxvpezgor.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtyiulsvod.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvggpwytc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtukeqisju.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtjxayvind.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtpxvjbzlu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtxqkeppgn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtetadnwwd.html


<!-- 参考信息 -->