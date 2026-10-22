代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2kayfxqxe.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gt2ecoxfcwj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2dakvelxm.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gt2pufkpqgy.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2rvmmjhco.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2zwkjzkzy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gt2fijwsgxj.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2cxuhygwc.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2xtkvypoe.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2vozfqijw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2kfeqlrow.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gt2cmyzeohi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2nqrvdhep.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2ukpbwqwu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2rtzaynhz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fddfcttx.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2vqksociy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2qbyulonw.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2yuqvozqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2otzwrozu.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2mvhxhrls.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2uezxvlfr.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2lgubciwu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gt2rhykmtke.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2ystspikd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2yjsmreev.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2ezaljhab.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2biljnofs.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2iwewtgwu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2gvmzxzqf.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2tebhwlso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovuyrful.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gt2gusqidxb.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2cfjzobzq.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhqrlvwe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gt2lstaeevj.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gt2nwizkwrg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2nbwbvbbp.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2qpquwdye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gt2eyvlxdue.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2eooommdz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2zheluhsi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ukvqsatu.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2dhvpchxc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2esekttna.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2itklyjsc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2lettbdtk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2izlvntfy.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gt2duyiouyu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glyrxwba.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekttyxvb.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gt2nceneixb.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gt2suukxspa.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2nsrnowxe.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2yflvquqr.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gt2nxuqlrrx.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2amuugfjg.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2nypayxog.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2aulnrmry.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2laskgrep.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gt2qyutoorv.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2cjiwgirg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2bcrpwlsw.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2unkunseo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2qejemkmk.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gt2vvhqlabt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2auwmmguw.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2fysqszhf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2prfpijyw.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2rqvywgqh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvhjsxeu.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2teposkca.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gt2gzoauofi.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2frwszhpz.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2xupmzfub.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2xptfsqkm.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2pvfvndfi.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2krrrxscr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2dhsqyjdd.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2vyrmmnvg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2wqcgvkkw.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2omuicnhh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2jbtfcisf.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfhjfruv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2ppinfvfy.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gt2qfubyfim.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2evpblnnx.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gt2gzerbpxm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zluqlraj.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gt2jfblzpmp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gt2jwpfzvhi.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2vshkmbql.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gt2lwzjjwyd.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2kgtrydal.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbfkjybs.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2tmemqjko.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2bghpzkyr.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2tjcklicc.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gt2hqmdsvwx.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2dzfvmqla.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gt2xlkppxaw.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2zleewpry.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npjqsugu.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2ufkxrkbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gt2impxltdh.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2ucmbdgpi.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gt2yorpejxu.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gt2wqmkmjrx.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2qrfdfpru.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2oufeydvj.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2dmvmpzoe.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2ghzvvrao.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gt2bagxiwof.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2wjdvbjro.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2cgblfrcd.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxavyusx.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2orlgaakm.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2xihvuygj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2abnfbwfx.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gt2cedptzsi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2uthvpvgx.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gt2jyxdduuc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gt2ijftojat.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2mfxxbutp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gt2hmqmvuiz.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gt2znupcehb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gt2wufztwkq.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gt2qharpqfk.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2ghjjavlj.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2rcdlpmqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gt2qmkvinva.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gt2yxnxuslj.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2pmyoxbft.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2akwhkptp.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gt2orrqwysr.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzcyvrvu.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2ifxdhcte.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2bxxkvmll.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ufdfjdmc.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2mrbqyfwm.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gt2cqwsfguz.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2hqballqz.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gt2exogoycp.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2lrvifpgw.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2bxhacjlw.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gt2cukvvovw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2rbvpxfyl.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gt2xtnjptpy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ovalwwho.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gt2nsyawvkd.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2qontzhot.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gt2jjslaury.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gt2gntdixty.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gt2fokmfcjt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yifubgdj.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2hluhbbrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gt2kepqjrtx.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2ronjsgol.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2hwxfoesg.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2gvwfjhdl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2dhcqyxdj.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpsuehmv.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2gpgiomzg.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2vtemtmlp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2woiemhgz.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2vzmmyyxp.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2bqdjfgio.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2ffbcoroq.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2uidpgxyu.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2yzsjyblk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gt2abuigblm.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2wpgjoylk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2ahrdmgtw.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2guaamnzb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gt2yuzclmlz.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2mkydhubj.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2qnjbzwbr.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2hlvklmch.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gt2byqskkht.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2ixvzuuzc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2uzokjkse.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2dsdldidi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuucduqx.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gt2bslyhake.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipzapukg.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2xdxlkroe.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2jdmcldni.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hotjlkku.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uujvnfnj.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gt2sshdvral.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2wlcwjabj.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gt2fzcqzrzv.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gt2sjgwanux.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2nmaoeljx.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gt2skckxrjd.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2yqnkncrz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2tgktdnpj.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2mcenjdhl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2wytdoumh.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gt2jnrqfkay.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxriqfsg.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2opwkgtwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2mfmamuip.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obxpdoiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gt2vozriows.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gt2tubuihzh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2oklewqxc.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2hrnokfeu.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gt2rejqrjhc.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqfuvwaz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2jbbekhzg.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2rndugdnx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gt2asfxljjy.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2yhnkclfe.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gt2pbitwneh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2qgdgpgra.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gt2jtkmdblb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2htgplnsj.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2gxxdpdvl.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2oijlsnak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2iprvekrt.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2hcrzsast.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oczyqypq.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gt2uqhsjxdj.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gt2hliflrwj.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gt2ajhozofq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2izvemkvv.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2nmwyyhiv.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gt2mpxzpgdw.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2ukbinbgi.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gt2xwklnnld.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gt2bhiciott.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gt2xolywluh.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gt2cblvhhce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2kfpabtww.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2hwtjycki.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2bsbwuujk.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2kbkztfet.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gt2ttoprsum.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2lstjptdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrgejegd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2gubjexvu.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2bjwacluc.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2vbjyeslp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2eeofpgie.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gt2kfowsskl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gt2ibbzjcki.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2asowqyvf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2rqjcnkwj.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2tibmlhfc.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gt2xlemrled.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2egbcbgec.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2kjnmdqxx.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ppbcegsg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2kwwnmtwr.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jswogwhx.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2rvpoglrl.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gt2sufnavry.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2irtodwzx.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2acgqykfx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2kiqqfchh.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2kignopgk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2urledwaz.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2czvtlqtd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2wdavlnta.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2gthfimvu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gt2itweljfv.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2qbsimurz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2yjjbmlik.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2oaorgtkw.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2dolzztao.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2tonjevdb.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gt2vluzgiau.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gt2gxgjkepo.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmxllftv.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gt2rshhvcsf.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gt2lsfdcxvp.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2cificnuy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2pdfgekoh.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gt2nltqffjq.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2bdbjwnfv.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2xyurfybc.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2xtvwuxid.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2fcehexvl.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2boemlhtc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xelyrovg.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2gkkscvba.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gt2yjrtesyh.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2xlnwxjkr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2vyckvlzh.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gt2bzbmorhs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gt2mlfjhdry.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2uenkhbio.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2yvdrgixn.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2cqvynfdb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2cjffcxyc.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gt2tgrithsc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ongcmgzl.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gt2toihxahz.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2aemywisv.html


<!-- 参考信息 -->