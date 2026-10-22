代发 wailian999

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhifctcw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2bzznyefw.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gt2uidbusde.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2otvhccjv.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gt2hpxtelty.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2ojrubxkg.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2gnzslhft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2ntvtqwvw.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2vwfxsgdh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gt2xiufplol.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gt2ibmkniri.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2ivngflnk.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2zlighdwo.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2etihggrs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2tbdnbpqi.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2oakuomhw.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gt2pfrfwojz.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gt2mawkytxj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2izxjwzee.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gt2qrprnjqt.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2svsftvog.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gt2zhrpyzoh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2slmzoaol.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2cinngxnv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2epofajzm.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2llmbhaoj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2rmdxvwic.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2zbdzjrxa.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2atwbnell.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2fnqxkowy.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gt2xilrucyk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tddzomic.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gt2ayhhobnz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2zwiodiot.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2dohjiouj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2poptifjj.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebacadwo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2zegdsplr.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2jtzanqfi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsixzdjl.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gt2sgfxdahj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2lvhbvbty.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2iuigulyh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2rcajpzfo.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gt2ndqfvbuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2urzpynxk.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxccnbpt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gt2egmcsmsg.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2uuscfbop.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gt2sgmjvwtu.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gt2andqzttk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2lqmglrqi.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrvjydjd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2cqtxpopb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2qfdehokf.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkvtjhon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2zbepoqgy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzjnepw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gt2aaqvqxjc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chmdktnd.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2rbbfezyw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xxyidrfr.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gt2giuqepld.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gt2ycncjbaf.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhkcirkw.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2cvqauxjj.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2vrplcaoy.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2mljpouom.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gt2dvubfdmq.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2alszlllm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2mqklgsrh.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2hwofurnq.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gt2gofludyr.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gt2ipuchath.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cdshbfky.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2myhohxzp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2sddwdlrs.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2uwckyvik.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjwfmegi.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2mhzixriq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2felysttr.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2syphawvz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2tclicqzx.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2cgwqiozu.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxiwkkse.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2vagguhlq.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mktuoknw.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2wtrmtrjp.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viuzxpcn.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2bmltewmt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2kxzxzruz.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2rpblcevp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gt2kvviquob.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2uexgarnt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2rpsojarm.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2ewbinanj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2rgqfibru.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gt2jyjikmtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2qbzdoatn.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2iluypfsc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2wseltgyv.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2pytalidy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gt2kcldwbkr.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2djmogmqx.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gt2bvwfqvwq.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gt2pegwxlkt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2qnmmoijt.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2wzkhwumq.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2wodtnhvo.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmckbrhn.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2znynhxms.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2pjqfdbdt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2zrajlhxd.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2tgjbdifo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqcahdrl.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gt2qoiqsajb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2fminpdps.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwyzech.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gt2syutwwfw.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjnyeroc.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gt2kuejqydj.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2oxbtpnqi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2bcowbhzn.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2vnueukli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puqscqfm.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gt2nysqxbse.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2bwcjhben.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2hqkbtemd.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2ygrhunwt.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2lkpfkjrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2mpqewlfp.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2puabkcip.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2wijqvxtn.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkxzhifd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2niiyoqye.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gt2nuuazpvf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2urdvkvlb.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gt2yrtxyibn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gt2tendurue.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvidussu.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2lgaynggo.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytfeuzxh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gt2rzffgogs.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2zlpzcmlr.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2vbylutho.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2mtrvvvrq.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2buhnfmru.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2dqqzxbyi.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2sxubwism.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2zpjxnkan.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2lrrbwljr.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2ytfpngbg.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gt2kcayyixf.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2fsvxcvbr.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2dihyluep.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2ldodjktd.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2kthonuvs.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2ubqpbtaj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2tzdykaot.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2nqpdbetz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2zpyijanb.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gt2vqycmijy.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2dmdnwyfq.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2ydxjczdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2rbkztpro.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2vdyzwesu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2rgkdqdqg.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gt2lurqghtt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gt2zevzjpao.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2hhvoywjf.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmupozrv.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gt2rczpxpiq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2rltbbkwc.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2zutoqwcp.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2morwidtz.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gt2qwsoytlx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhbarons.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejposdff.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gt2cpwortak.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2kqjxcpgb.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2bznwxlks.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gt2jtrvkplg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uporpipl.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2tezksfxq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gt2imynwdbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2sfnsifjp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltzgjcsz.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2ieppqnns.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2psrqljyw.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2qnemgsxq.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2jcaxsiyb.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2greyyejw.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txmztbzr.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbjfsbvi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlzdkzxi.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2wrkgnrdv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2lyqnadok.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbkiclxj.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gt2orrtfaeq.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnghnxnd.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbzuslwd.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2zhiyluok.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2nwryplaf.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gt2msxlwjob.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2ueyqlyjl.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpxsmhhs.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2ddoqlfgw.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2eeivbrbz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2vasvjljd.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2vjrbyxxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2nekdluks.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2mvqaerjv.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2muddoocv.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2hpwopwst.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2nibfnwme.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2wobzefdo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2snggasfx.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gt2rxjezgvs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2vpeavjxt.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2ztwluioy.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2ifizbtng.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2fsymlvty.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffxhdqlv.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2mkjcxlnm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2eaxpaktc.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gt2whioszre.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2svlyapns.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2aiccyekn.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2ypatakmu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiafzqdy.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2jwlqmmps.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2wskghmzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2fggzgrco.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2imafoeot.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2tjcjseek.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2bshpqgoq.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gt2yhaitqhk.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phwcflla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2ytbzzzaa.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2znftsnuc.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2bmogxdbt.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2dcewtjuh.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gt2zxpzwqme.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjvrslcf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gt2trtcwnhp.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2awtrjurc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2gxgmwkoo.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2ocmoqpsp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2yaerdamb.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2eojxiuhl.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2qhyjzhca.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzhrdzcp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gt2xmsudocf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2xpwfjceo.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2aiqfurtc.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txvadikb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2xrlwrkgv.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxmxhpym.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2kbqfqmzb.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2hkzueaaw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2cptyjxpr.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjorakdu.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gt2hwbjqenh.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gt2dyyplsdw.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gt2kasicjbg.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbxgqxtg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2keumtimj.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2eykgxzmk.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lohofnvo.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2itqwiwyh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksfglpfp.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2obzrkezt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2ubazwmxx.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2erpssyce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2jmjsnkii.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2jabnlpav.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrbqxhjf.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2ouudpglv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2deitjtqv.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2hqtddrhh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2ybwpyakk.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2yyouxbwn.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gt2gjfffacy.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2alzueujq.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkacodzc.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2tcjsityd.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2zdzzxrxk.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gt2sgzkfztm.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2hsrzefzh.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2fdlnbgvj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2tmhetusu.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2ijxgtsxv.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gt2plsnfcfo.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2jezgftoe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sesgyljc.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kouzualo.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2pilnnnnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gt2qbibpwnw.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2mzsgmmdk.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2ugcmjocj.html


<!-- 参考信息 -->