代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtemguuans.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtinppdgjh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gthxsrndrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtgvflelbi.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gttxfhzyqy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtjqdqxgom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtulurbaix.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtfnzjlrfb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtcoyuqotz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtrybzpsjn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtfbdcqjaj.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtahgroedb.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtzqguqftg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtkemwyduz.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtrutvdxit.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtngkwqfig.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtlmuvsofj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtffmcgdvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtffreducs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtedltfygj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtsaibtmvo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtudxvftqn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gthhzwriru.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gteayjifso.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtukeqxavq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtiylumujn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtgmazewlv.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtwxruqzpx.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gtafzzmlvn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtfqelrwef.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtecdzwzkg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtgtwidvfj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtuajtrbbq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtzhajbcgr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtytlhjqoi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtcaipcnjd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtxghwcczz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtywtysidy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtumgdlkcv.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtvwbqbbdn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtjuafieyl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtfviigali.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtnjgyxghi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtjnojxbmt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtfemiwwfx.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtkffnqcja.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtkznydfml.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtankgbbhp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttjsfxonr.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtwhvwiudf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyizowyjc.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtlobjulod.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtwtsqzajr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtvmokirot.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtklfwusiq.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtctpjgycr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtifnadbnr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkujbttvc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtzyumsbgq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtgrmnshgo.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtlgfcxyqp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtwjpekaqq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtwbmoskos.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtzytlqqgk.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtepsifxik.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtnsndkwmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtpxaxyghz.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtiriwidyt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtyjqhfezv.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtfjcmaoia.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gteloeglli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtymhykbnq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtjdakehxz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtbqbywnjv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gtohmzsvbs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gthptsajxh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtpyjjfeif.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtacogfipl.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtpmzdqqlj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtdaflewxy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtqytycvkt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtgqleyuxl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtragigftc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtbanxszju.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtfyaxtnxf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtrjdqovab.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtixoosqrc.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtanbnlmqa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtzwlkpfrz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtbgzwisrr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtlmofhmia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtqtmccien.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtohjmhnxi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtwagvqnnb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtxekykgwp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtmbcapdmp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gteuhwtmre.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtzljxhrqh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtfgstfsrd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtlxkutybr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtauzjfccd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtpapuprjf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtsolhoulf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtkmyromrq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtfbbevyqw.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gttamwkhgq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtjdumbvbs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtqbehvclh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtqkuhozyv.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtxcrosphk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtriszszjt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtobrsswez.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtfnjmwsry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtfbiarhyr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtctdxtoak.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtbqxkohqu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtadmoewyq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtxrzwvsdq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtslzrlsqg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtobfizhax.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxrogisi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtjgzsrfem.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmngjqnfe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpwdnedqx.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtutcprgkt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcurmnfdo.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtrlexkraa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtqbizqhnx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtdvukdnck.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtfhkbcvye.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtipripqna.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtuvrcczyx.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtvtdahgii.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtacvrcsfz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtrzttfibq.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtlmmusddn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtvefywesp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtjqjttlhd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtjdllkqqq.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtdcvjuitn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gteutqyrom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtbqbfvqrf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtgmubgqvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprgabvyd.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtaetbkpon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtczhoahio.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtdjiolroj.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtmtinhfxk.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtungqjhmo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtwfgrtsik.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtrcbcxvhw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gthxxlwjin.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtlcqgvfcg.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtfsqtrcnm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtyrpawesb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtqsawggdw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtrbiguqed.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtnoizmnwe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtnjqgesai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gthaodajqp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtefuynnor.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtzkouxtlh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtjpttfqdy.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtibyweipi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gthbuykuzv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtrtvjfasr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtxhxpucqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtcdjzkztn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtiaxusjqy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtyhcitmtn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtntvsxxcj.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtucmbskrh.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtwjjsihnl.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtjprlsfdp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtoouveeok.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtrwbgphqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtocmiwhvb.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtwooxevvb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtyzdtokux.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtxogavjxo.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtbpixvzln.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtxgruativ.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtzfdlgvzp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtipebuwwp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtxiivzfbt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtsunxdjya.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtjhesnyce.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtlzrojanl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtlwdtgtkz.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtscaqekgn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtmtdcwdvc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtmytqtipo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtuxqtsubj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtsrlkzppz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtmtaqvrwl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtefprgeic.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtomjzxped.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrdcwiis.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtjbmtrkap.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtjgaglmog.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtbsxquvty.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtgcidgdcg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gthgckgkbv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtkwptboyl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtumjdctvq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtsyogjbwk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtactgairg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtcmbhxolp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtvvhypgma.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtphgdiwkd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtxjbjpofd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtgzioejxd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtiohtiguo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtpifgszuj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gthpvbtjua.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtysydaywl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxaqqcnws.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtqyiihsuk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoioqtqiy.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtiaceyvxu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtitdapxud.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtjvniegvv.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqiwtbuob.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtoawnroya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtjolrsarl.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtdbhassds.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtcszobvij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtlleygbbx.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtasjdxngk.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtlifrcynd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtuqxqpvyx.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtesyivefa.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtrevoxvrj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtsaidsfqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtsmfhfevf.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtlsgezcax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtpusjkyvi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtywiwdxgb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtjktqiati.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtpuenzuag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtswpldezp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtprgoshxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtvqjyjrtn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtueddddgz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxyglbuzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtboycmigx.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtxxwjuerb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtzkqdbgtf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprlowfgg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtvonwetnz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtpnuxnkne.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllryzkod.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvavmzlot.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtvpaxrhcb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtutpvuzxc.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtijwkyicr.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtgyfptffc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtcyuzihfl.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtvcjbaybg.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtpmkcgvqf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtjmvjtxxe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtniazgbfq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtygkneqff.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtwurfwrly.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtjdawchxb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtrumqwaxx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtpsjgpvdq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtosshldbl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtlnifwjkr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtqxlobfom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtnerixzwx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gthzbjbqxv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtwmclperf.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtwhtnopsj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtrcrukyhe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtudxxsmlh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtqunyfjyo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtdhokmxxv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtxxqvrdly.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtnrrawgig.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtyurgmzed.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtogadvxft.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gterqihoph.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtvhjxekge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gthlsiqtzk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtfdafvqpq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtqgiiijtc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtnkqrnoni.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtdhofaaxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtcghupnsv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtlrsptfto.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpczpzuvy.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppjpdnof.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrqxyjjru.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtxwmdltvv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtifzcrlty.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtjkqfbbdc.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtsfzmwjwa.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtestmuhli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtdbyuwrvm.html


<!-- 参考信息 -->