代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2xlfvpkew.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2fjfdefpb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gt2hefguzan.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2jqrygnwq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2iarfgopv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2qslnxjyf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2vpjicpjn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rxzhqqch.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2qqbodnzl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gt2kqurhfbf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2nvienprs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2puyvtkeb.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duowmzdc.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2ksbtggck.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2kyrnjxnf.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2tnwllvxi.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2xjuqksxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2domkvwov.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxhlnnmg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2ujiddigx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2jdtviaex.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlrylbvp.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2jbmbfinf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2tsxznxtq.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2fwwzwivr.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2krzkfutq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2boaehmpd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvemqrmn.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2jpzyhhnw.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juqejosf.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2lktniwqz.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gt2cqexaymf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gt2hfbsdrsu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2ewwuzzfs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2nalljozy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2uiaezknm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2wyelxvzw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2lvjujhnz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gt2kizhghhb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gt2tdfxyomq.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gt2utwiyrup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2ukiapknh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2sphevsny.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2szrgofvi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bacndquz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2hzqehpoo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2zncqilnh.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2vyrdgtkj.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2rfhuaxkd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gt2oetvnftu.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gt2rvxuojtr.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2qolwkoxd.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2sczulkfv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqqxrnmc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2parirhzl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2idqaqrqc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chmqbgol.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2hsqelnhe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2iroiwgov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2zvtdzwap.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gt2lmyadgiy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2zdqmtihf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2tlnvnxpj.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gt2ewanqftg.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2apfpwjma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2dornjabu.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2qgkdjqiv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2ztdgwpbm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2iqacjpqs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gt2dgbkeqbq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gt2udhvirzt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gt2itiphmlk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2jnwyafmr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gt2hxietuwu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2gfslfgjv.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gt2rbqbngvn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2fweauhdy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgrsvzzo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2ngalizpk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2yoyacyry.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gt2ltzbyfmm.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2yhcnrofw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gt2shggwvkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2woramymv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2udxvbymy.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gt2jojcnfwl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2logtgzqz.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2jhebkwis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2rfeitssr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2qhsbrzoz.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2vqqrmgnn.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xbvtwuce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2pualsxcp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2edixhhrr.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2xfqcbzzy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2nqvnwjtn.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gt2atywntmm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2gecktlcv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2aqgreubw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2zamoqdiv.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2peaiyfib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebhaeszv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2nxzhtutz.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2biwjmtbi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2ixsjqbyh.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ktwwynut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vewnvucz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2lrwqnxzp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2neevzbuj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtqpabqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gt2ettvculg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2covzabfb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2lrztxiig.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbviqjec.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gt2xlvchiks.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gt2haovtahe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gt2byonafpc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzgthlyo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqwivlfa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2rkexqrqe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxqrczti.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2fxwrhxjt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2vhikorct.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2gfhfened.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2bxtwjmwo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2vxxyjqus.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkcboky.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2lboprtew.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2atnydisl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2gsqyqioy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2namrapvl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvtwutbs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pckuadrx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2vlokbvrp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gt2urtdisfz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2ltlhvhar.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2xumqawez.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvororpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gt2amjrmdqs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2nwmwvdvk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2wxehhsra.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gt2nlkuhkxd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gt2ogsbvqzs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2acjjjkmp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2ghwcmsgo.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gt2oghijaqn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2tmgwcwgy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gt2mlnepvqh.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2gegbpdew.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2epofseug.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gt2traltobn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2vzbgytkr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2ykszddgd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2jvrovlpm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2ntpdndim.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2vdvyrgsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2ixfykank.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2maformrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2eiztywgl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2keyzckyu.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2pmtwnubv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bbktgusw.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2aiayyuor.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2toundkpy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2wsnoqzmn.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2cgzluern.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2fauyzlpp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2cnkreqcl.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2stutwsdc.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gt2ihpfjkcd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2usfsoaft.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2jekiwozx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2wfdhjsdt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2qznwziue.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2wcgdyunc.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2dpjcqzda.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2aezdairq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gt2emmrghvn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2eyrkmjge.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2qjveomye.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2skivccee.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2xumvspws.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlzhudlk.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2fzlvvwyn.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2dnxazxld.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaqkljsa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2dbbmphsx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xizsxrtt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2ydddwudc.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2fevoyfqk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2idzawykt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2iismzidz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2dhibmyxc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2sjxribxv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2yjywyeqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2bqybbzno.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2tztzcfep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2cqfbictn.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2synsrhpg.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dugtcabz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gt2jyquinet.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2drwglggb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zenqmnid.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2iqdusebi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2yycwouap.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enheriix.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gt2imwxmavx.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gt2fivbwhcv.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2laoxaypo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2ulwqgdla.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gt2pjuldmzn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gt2imvqgvwp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gt2jzdzqyni.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2zwqmhgpe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2cbrudkqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gt2lqgmqedj.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2qlujvzew.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2yngtswfg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaaoaesm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2nsxxanwu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2bhgatbrj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2ijppdsqa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2kyngwplu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkzgtcsa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2gzkyrcdn.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2mtzifmcs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2ebaqpput.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixlfjvpy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gt2ldtcsyqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2tjnijohz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2untkbabm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2lmrymwfb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gt2hxukanbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2sqcfcwus.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gt2sxosdnqp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gt2hywuqife.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2ebpishnp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2uqttqgfc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2knhvdbuj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2mzrzllno.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2kstrjrjb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2txwnzaqv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2wnyitpms.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2vmvwtjhr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2scstlhbv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2utlqbalk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2njoqesiz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2zwnztyuu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2eldpdpjx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnxzdnuf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2xxrubviy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2yozurtsk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkkwbsfn.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2dqagapfo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2edndezlc.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2yxbaladw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2savdwqwi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2ecsqipwa.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2oabhylpb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2fhlnkxjw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2wcnqmdha.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2xsbgxlmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gt2gvdojcls.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2uilzlktz.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifkvfopx.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ffmufbxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2rdvmcayo.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2mjtwilht.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2hotaohur.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2bofpgqzg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2whfqfurj.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurxdopo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfekegad.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2jwihepzc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2glhfhmfj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2cetuzpeo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vogrosts.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ollxqufi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2gavflpek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjhemqdm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2vmvpjhrr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2budrdjyn.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2qzhmyvbn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gt2jyrcmdrw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2yvyfdofu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2dnukqoke.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2mutahynq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2hxuhidcd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2dqrhffai.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2ifrejdps.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2gzqwrvgn.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2ckmklext.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2bcflduxh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gt2vcqawxmk.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2djmqdhmv.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ebehbepg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2zyqejets.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2lttxrhqj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2eyaqnjwh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnlrggxs.html


<!-- 参考信息 -->