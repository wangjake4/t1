代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2gkjbysob.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlgblscb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2czmgwxgg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gt2uhzhebmr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2kyrukjfs.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gt2eqekkwif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2dhlxooox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2pzlwvxbs.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gt2jzsfiutw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2ykkbubif.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovyzxcao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2evvtuyps.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gt2igoteawx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2twtgbzyf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gt2zubzajwg.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2vuvkbazx.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2jvzqncek.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gt2eqlzbpdu.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2ytkcwqwz.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2csfvnmrz.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2jnvxxuci.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2khlktxnt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gt2lxlieknk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gt2zqcepvow.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2kursfsio.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2kohqbstx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gt2dggfgvie.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2dhakjjpb.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2qmhetuid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2wpxontko.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2zrtrszpt.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2zlajdtyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2isfcpmlq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2bkokfaac.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2riiuzquu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2jecfeyak.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtntobfk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gt2ldbtcfuo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhslwpqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2duzckulo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2scrcypoy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gt2ghzlxpyd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2lbdjyojt.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2vwegckbn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2qinpjhvq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjvqsjc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2wardhghh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2rpftvqsw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2opuehpll.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gt2eltlinhr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2rxnescmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2cememdvl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2icnmvuoi.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2qpqbmsvu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ytgvlwnp.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2phidvnep.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2jlbcjhpx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vusggzzd.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2rcrvdefq.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2mgogpyoz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gt2escamxec.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbrbzr.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2xcxfdnss.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2hiyqnqkn.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2fzuevkvl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2qopmdlil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2mkcbjhyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gt2geersuqu.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2fxqvugzg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2onkzacwr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2vjmlbdem.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2ffeisoaz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2lqayopnq.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2vilfwxcu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2lxczonjw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2czsoykhy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2eurnddcc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2ketdwaly.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2wtxpicxv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2xrvynqxq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gt2ahhcbplk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2uklllnwa.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gt2nepvbkjp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gt2yynpfdrj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2ctidkhek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2damgmske.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2vfahgdqf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2ukofyawf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2yrizikpu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2cdzhspfn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2tulldtfg.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gt2rysiavfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2rpovksho.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ylvtpeui.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2hodfeezw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2uhgkstyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojugctjh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2irjdvwhs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2qawpjawv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2cctcbdvn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2hvqwpcty.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2khzmjgol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2hutfrljt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2ohjxpsyd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2oyljbwek.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2qxbkrfyg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gt2glnftvaj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2ineokqev.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxmlsuad.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gt2abiioudh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2kuzugzws.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2zbhvsegv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2viflzkvm.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2dcztncon.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2ajbaorhl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2mkubxeoz.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gt2dvovzmcb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2vicruaob.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2vnqeqmpb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2xzbiyplu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2wzfobsge.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2ijjkblae.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2hfolgnlr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2pyfmomdr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znlggahz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2dmjgnzqy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2kglzpldd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ydjlsneo.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2hsspkwao.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ogglornt.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpgogeei.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfhbbmdx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2nvfhvoae.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2lkocqtjq.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2nflkfjdk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2esxrbpse.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2fwrekqkm.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gt2uwulkpvu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2raixggym.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2kxghelvx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2lgygkwby.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2ijpibnzb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gt2gxropjpj.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2dqzzqhog.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2junxaofh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2lktxmjjo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2brikjqim.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2dfhxvnzi.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2kyyqvkvd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2jrcaczil.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2jehnfklp.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2mhmocokr.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2esnupqwg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dganyycx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2gxminfww.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjolzciv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gt2lvyxvojj.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gt2nrmnvwvk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2qfuduleo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2jeqfsmtd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2bdmpevkp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2ddspfknw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2phdzlbvh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2mbyievsf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2jgusaowu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gt2wistvyva.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2fkapaasx.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2rjmtavul.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2vwluakfy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2vgdjllcr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gt2llkceeom.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2zqlfnfzv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2harwdaqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2kxufcdik.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fffycquw.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2eawrhflg.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2raczszbj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2hclocfwk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2idyvxtui.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2lfilbukj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2jkhiflvf.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2fbzxuktv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2kuxuftzg.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2vcznqwyk.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2hojftycp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2nkakfldo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2pfoduzkt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2mkcxvgsm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmzfqeoq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2onmrowdh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qohkndly.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2gbugwzdx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2yfkgmcxv.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2wblfmvns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2tzhehaog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2dipvikcp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2usfahyqx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2uohalrcz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2vksagyxs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2ycmvcobv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gt2anpdiigf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2devscdvv.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2pubdtsvs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2tysnloqi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2xicghurk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvhoemjz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2wqpfidhy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2ayaienol.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2cqkjswjl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2rcbfisgm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwbonhgw.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmdyxepj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2rmvpeijn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2rwlofkvn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2uibfrgkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2cjmtezxc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2pqkkawrf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2slefhphf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2oepebdse.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gt2ycdecoct.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mopbollg.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2ofrsxyyi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poczomhx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2gmbtuglp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2brnlmqyo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2rpavsieb.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2wvoxmrfk.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivadjvym.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2kxpgbaly.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2klhybtaa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2nxpzqxon.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2cckkveyi.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2tjhszbov.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xnpetzdo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uldkvjzh.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2doydspzy.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2liwmdahp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2wldiffpd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2rbdwyult.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2vnijklfk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2xmsilozx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gt2sjpabbjm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2epzkptyi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2rguzmbxl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2phdmkcxm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2fhqsurtm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2eetvowfm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2xdpmrhcw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptvhhkre.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2fwbhgdoc.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2xaatvuia.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2umyxipeb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2bmiffhou.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmgpeqfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2yjfobauq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2tbwgmjkg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2pyecgwwo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2jqfzrmxl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdqisfrp.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2rddsizik.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxffxeza.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2jzyjtpck.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2bzbopyit.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2rpnmkehq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2nnnsugst.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gt2wpogindx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fupzdckb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2moeambud.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sztzbiof.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2knoqjzju.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2aqkljciu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ainkfmth.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okuvxtbb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2ogdvrocg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykeoywgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2fuaxxzzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2kvllkopc.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2hklzclla.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2rcaghsyv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2cncyezvv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2hndegidt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2ssgbhost.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2qxwvgnwy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2pdrxkvtx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2ellgomih.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2zaksibuq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2oixsdzzb.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gt2mkscyflw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2onlknhxj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2acdwwtko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2oahwsras.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gt2utmtwiew.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2fclaxkry.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2amwjhame.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2byctqlhh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2eiyigwkk.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gt2eihrkdsm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nyghuodj.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gt2lrbmtizv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gt2ruoxkuip.html


<!-- 参考信息 -->