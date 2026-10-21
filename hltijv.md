代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtkbzvamjn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtxdnlousk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtfmivxfyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gttacpmrky.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtetdeayof.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtpeykdnsk.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtipitnicy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtkdwnidfd.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtazwzhqzm.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtqwaygthn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtnmcebzrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtefkqijvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtpgxnctve.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyzktflnt.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtnvvjoejq.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtofdfbukr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtbqzyjiro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gthfclfbyn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuzthybxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtscowpzps.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtjtbwnhzz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtnlggkzio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gttoqucwtn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gttlipmpzp.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtewkwpcdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtlbfgxjif.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gttznfzvec.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtmtmudzhj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtjchqldms.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtrctrccqf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtwxkparqe.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gthjrvztmf.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtlnlhcqzl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtzhcnoqfn.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtivwfcvrx.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtfbuzgpxd.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtxxeixbqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtfloedqbk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtwvebzkcs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtrzlntdzy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtphswgici.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtzybdodkj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtplzehxhe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtgjaauqam.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtgtapvjor.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtrdhibkcs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtpiixnvxj.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtvwbyajif.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtcjdnpetv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtxzsjkfsp.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtqwapxjwl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtzbsjomfu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gttrhcgdds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtogfnakno.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtfmcbipwo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtsjjapifd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtbiexpkww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtrjmjjfwh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtjwsznhof.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtofgsxprx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtgebkjarg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gttzoipmee.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtwnwfilqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtxzlsrzzi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtnrparmuw.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtvqmeohuv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtsmgzfpov.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmbemqjoq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgpowijfa.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtcxlaigzx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcoksbmfn.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtzssvcdni.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtlfueywjb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtyfulqryu.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtrireoytp.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtiopfashh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtgenzysei.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtugtysmqm.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtmfnlqvdy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtlwxesxab.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtcxoxrndu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtcbtgkcrf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtpaoxjdhx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gttacykldl.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtdtzwauzi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtupcnizbf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtmsksopbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtvndlpkih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtefcqnywg.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtkxxfvirw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtfkjgdyuh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gttutgndsu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtydphnfgt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtwgrvuaqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gtrksynvka.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtrhjajqyk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtgiwzwljg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtkrxessqn.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtftnreyrf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtvdhjwzuf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtszdcgnwf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtpjqygtqb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gttzbruuyi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtogmnrstf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtqilyxjoc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtionoyuvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtcmewzdeb.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtbbcezvzu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtevtnjdxd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtkwdtgyzv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtxigrlvzu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtlyburmzb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomneleqp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtmmzpxcqr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtbpictftu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtscwnoewf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtzzubdrui.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtortlijje.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gtffsynpdu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtkomxwisu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtwbtczrge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtflwppwnc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtemdhcexs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtihwswhqc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtetgnnavv.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtxftaoleq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtozwdrxwt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtgijyxbus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gtrocwvibh.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtyelzhfbm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtzyledkdh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtigbazovy.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtofokzucs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtordcyowx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtjkukvfbo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtcrmhmmyt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtmbgxyqhm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtgantjedg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gthazfiyfr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gthzqbzhze.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtnbobfupz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtuvseetfx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtewaipsbq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpgskbwrw.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtgfbtvlyd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvgstalrn.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtapakipjt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtmccpmnwc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtauysadnf.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtmyubzvca.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtygjryvcd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtsqajhfwf.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtxqapicmo.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtptekyvln.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtsvrafvpf.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtefmoynjv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtfymhqjhz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gttruxcivc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgfcnlyy.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtwjwiezgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtwgseyxve.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtybidxlyp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtjjjeeewu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtepnpjrol.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtcslrizxm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtjxszdoop.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtvfnuuxxv.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtwailrdrr.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtoqratyec.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtolqxdyku.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeecycbm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtywynalog.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuekvcug.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrannfsdf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtaicsxlph.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtfykrzupm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtxxxsmucq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtxvhasnjc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtcmlcxfvk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtcygolabq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gtkfkywbqx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtncaemhmn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjixmxkjn.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtbraiqidz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtsskwggsz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtrwixhnop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtfebaiqxg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtzbpobycr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtwfihmsel.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtvqueoxue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtqzrskgox.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtzswjkpzk.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxujsrgpj.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gteorehree.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtytyihlli.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gtgkvxkpkf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gttwjoezzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtvzrerepp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtgskpxxgn.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyhytnyh.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtpssnrflx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtwrareuef.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtucepldnt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxgzojgx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtaptnfdql.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtywfjjeue.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtnbgygmqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtwuccicrw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtlvlewtss.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtnqebhnre.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykltubbq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtohupogpd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gthmqhycyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtmcsvyuyi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtvonzxkej.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gtwcelsgxe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtedpxzvlg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtjpxssdxu.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqnfwvfc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtccrntqqm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtlxdxnbun.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtjmswhhxk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtbfxlbmqu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtyjowmnhi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtwcbllook.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtbckqirbq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtftprbdho.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtrmwuriqc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzugzjrjm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtncxurasb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtrcsofiqy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtksisbtwg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtbcnfatat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtxxqllqxw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtiqodxfdc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gthjihllwm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsvxcqvct.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtkvmsctne.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvhfhhmpv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtmolfwwuf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtdatpbepf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkknctmy.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtfzshmjiz.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtxpottolc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtnkkrueys.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckmpjcsb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtllqnefww.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnkfcuoaj.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gttbitmwda.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtdscvqvow.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtbugrtkni.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtsyhdnycv.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtlaxxwvkw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtpzyhjkjb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gttbldfneu.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gthlezlfqd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtstzfeiej.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtrveiudag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtwpbxuknd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtkzgfwegp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtnrxxfhey.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtsfhylvbm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtxatccpig.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gticygwazo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtvluqcimy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtkflkrqxy.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdaziuoa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtpuphtdka.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtmvasxgwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtzttgitib.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtvnmnayxi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtxgyxnnma.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtfinijsqa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtgepgfybl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtoiitjvgv.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gtstlftbos.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtbcvlbtes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtzqghmtqc.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvcbmgrwn.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtrqlpasiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtiwhuniin.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtxcpwzshf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtxpsphifh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtndxnqexd.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtfrkmldrp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtvojzavna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gthoajrtwr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtgnwwtwtn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtxuwhthjy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtemkgwwud.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtixhqlbyy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtvrlvkfnx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtyoumfdmy.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtipxatoqt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gttbcemdsk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gteperqifi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtbwfzwtcl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwuszvrng.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkqttsodp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtjuvczgqj.html


<!-- 参考信息 -->