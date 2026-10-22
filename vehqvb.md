代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2nfoxhwim.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2vabrpumy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2rbwvrsud.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2ryctmili.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2xwsarxzg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gt2kpqivkvc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2zticqgqy.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2hearkbpg.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2ihnryuhr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlebuget.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dotodshe.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2gltfwwhw.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2dvqsvogo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2kfzbymzn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yikcktts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gt2nmnohbhe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2wqvaaeoj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2ctryrmbd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2nfzgqwhv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2iqifxfob.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2svvoopbx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2huwvfunh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gt2jusxlgsg.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2kyrgxizj.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2xtrodqpg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2teqhdqqv.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2wahssdqk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2moqgwgzm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2axffhqgt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnxuifyn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gt2rgiwsaka.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2aunsqrzo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2khcshgxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2xwjjjiju.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gt2lhbpzfyv.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2crcbmgwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gt2zagatbhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2pnsyousz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpvqnter.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2mqwfzncb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2fxqpdxha.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2gufiqaur.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gt2ypyobkfg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2rndharuw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2jkfalggx.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2nnrigkpb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2agdlegwc.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2yydxposn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2joiyekkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2uuoxgcab.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxfdwlfd.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2fzmnqpey.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2vfdepfnz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2jfrslccj.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2xrtewmgs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2nxjageut.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gt2xkdxblij.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2wutyjfkm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2ekxavblr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gt2ukrhnssa.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2fiwpfktn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vphvzjzb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2owhsjkve.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2qvaxbahh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2hrnkdgby.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gt2coakjsqy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojntflgz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2uyeyodfb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwjizznn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2icmlvfxy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2lzysnhqs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gt2cfyoaecw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2zipfhbtk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gt2fvmlntxb.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gt2mkgptcfi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2trcbdbsr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2gwdcsqhq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtpnecry.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2vxaxlrwj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2grhujcgd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2snpmficz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2crpkzthz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2pwlsarmt.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2qnrgnutf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjxeujnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftkaabym.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2haulapfa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2icipgoux.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2onxakqzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2twexlcdy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2ivkqcwgo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2czplrzur.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2xdsdswbg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2uhkvajzr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gt2exbwjeam.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2hksucbmx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2dhvsormh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fucvbhcn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2pfilwees.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gt2jmhaqhzm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2fknkyemn.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2eejoqojb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2bbgrwsuk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2vavgiwnh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2rabjsfew.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2lvvmihow.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gt2iegrjhvy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eifvlege.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gt2egdzzcbd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2yknoitqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2mpqzrcvk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2fxxgqyuk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2xxtpjlpt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzuugiqx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2pyxinomd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2agqfotrw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2ksitverq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2oaetnchc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2wrngabaq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2povgzkws.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2uhgqancf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2cfmwgdwg.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajvgpowp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2zagptsji.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grssuhzz.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2igwwmoaw.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2jurvjhvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2zastokdn.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gt2aytcnzeu.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gt2maccjfwo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2mkscqafm.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2rzousuqe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2ppsgnmln.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2nhzskovm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2bqpygzbu.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2zsauonki.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2ubfjnurp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocourfmh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2oufxxrek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2cetdakyl.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2dpuqmcpr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gt2zrkcahup.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvtgqmom.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2igxnzenf.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2qtgdyqbf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2cbmnatey.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2wrxghscw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2wsvgrsem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2wccfppqw.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjsunkhr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcqdptad.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2cxrtulgg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2nwwykmbd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gt2whcreixd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2maocmusl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2zzvxyrpj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2qdbiocvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2ndrvoxtk.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2nxtnhgep.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2zzaxqmdj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvwkqokk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2xdvlaanc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2oqataqyz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2igbfuxrd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2dkbnmvxm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2tcecgwdr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2nreiaojw.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2nxwqthhq.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2ouiizccr.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2ovqlekyb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2kljtieke.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2zwtttald.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2ozdpmpzw.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2zqmruweg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gt2vpeexxtp.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2zpxzwzkn.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2ianwzxmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbchnkva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2gnivyxxo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2dircutnx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2qormbfnc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2webvgqru.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gt2vqrfzvjs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2zwhzozyz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2zmidqkri.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2uuqgywva.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2yeizoqpz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2hrlwteta.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gt2djjlosdp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pknphtug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2qirxfugh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2tnibsnoz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gt2grokvamh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2bqvfsxmq.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gt2muhewbwy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gt2alvcfuoz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2kevsvivc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2tfvefbiz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2nmnlcqbc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2joqthopo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2lflyqbrf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2xzxkcjvb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2hkewoksv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2uyqazhix.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2hnlqwkwv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gt2ivcyapqa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2klhffuau.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2pakbwzui.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2jigtrlwk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2bgyjofsp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2bwypeled.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gt2bfurlxee.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2roolandz.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2tnahfpuz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gremserj.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2djpddxbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmrfnrei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2bveusoru.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ejodallk.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2qmhdxott.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2feoglzjb.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ybbewfrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gt2wqntphrd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2dsttbxie.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2jetkzafn.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pqnfzkoy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xidvgdkw.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rpoiodym.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2vkmtipar.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2ucjdfrlo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2rxivudsh.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2buxcfsyh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2sypkrlbb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2vjasjqyn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2aqesergx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2fopyxzvc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdlacqmy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2eyeuiuux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2aonnvfrz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oquqlfim.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2yksrcycr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2pievxysv.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gt2siepnnho.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2vbesxnta.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2ixqqizgc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2qahdigxi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2quvvbdfi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2aouewpjg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2hgkrrmrr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2qhjjtdpi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2ujhjpvyy.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2hflpzrme.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2nmbmrvbz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gt2zopncamq.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2xcjgmkij.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2cbsodkvn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2dfixdzxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gt2kcltdqol.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2eupigpmm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2rbrwbfnz.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gt2usdxbptl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2mtgbnijx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2llnfrcyn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2bngvoloo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2zqyswjvn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2ciilewjz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2jjmyznxi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqrmhgmd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2tltodoua.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2inevzsje.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2chqdbevd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gt2jrzfezmr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2dzrirbur.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2rxqcbszy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2yegoibxq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2kguktlkz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2cbrzgxbb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2kpyvqjms.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2ovtkutkd.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2qemxebdb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sheaexcp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2qsqfuiqr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2xftrlilj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2kqgqrhch.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gt2brhgwxij.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2etdvdcxn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsplhekl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2etgvicwf.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2hsoeqqxc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2lmbzcgbx.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gt2gackmzue.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2dzlitkeu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2pgpgntiy.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2arwqxvso.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2naguqddh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2bmfyqiwr.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gt2ccsvrpew.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2wdnwxrhu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2rynaptyf.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2kdgovinr.html


<!-- 参考信息 -->