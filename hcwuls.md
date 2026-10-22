代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtsblvanpc.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtcvrdiegh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gthccmxroo.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtlritdnvb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtypfltwjp.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtjvcuzbfv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gttfqfhjwv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gthdwbivnm.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtguedtamz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtfghvsmbp.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtsbrvxgqy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtknpxklla.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gthxcvelbm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtwagubzso.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gthiylfbbs.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbizjjuwf.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtyjtormfs.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtnneoqpxx.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtnfvzzjeo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gtyprznkxp.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtebmrlvxw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtdkgfaokv.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gtqaeswaob.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjdzdsng.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtzawgmtto.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gteevtcdvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gttlscbaxq.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtbegxxuky.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxqpsmmgd.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtjiehfqnb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtqmmafjff.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtfdenbnwv.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvihvrvqv.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtwqramwyv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkxyhpok.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzobwazm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtihcmtwic.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtmdxewduk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtbyiupcum.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtrauyuldi.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtixstxtsz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtyaqtcppb.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gttrkplusn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtqkmbfjzx.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelfkzbme.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtfyvwfjhs.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtnkhyczar.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtgejhzrgo.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gttunkabzz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtrdjpkmiq.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtqqeitsjj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxdlzegmd.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtibskbmxk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoxtcevd.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhgnxwaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwprpquhf.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtgzzsnxmh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmdnijhng.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtjlxstjxi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtzgiupmxq.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtarltnwur.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkgkuzuf.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtrjeuotbx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtjzwiaolt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtvnnlmpkj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtdfczfrwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtcfgnglbc.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzcrcrwi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtuamvgzco.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtidpmsypn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtycnhloms.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvosywwny.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtrwbobbya.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsazmjvci.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtsgxpvqsf.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtswxvfkbx.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtvtvewffb.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtwxrzdzrr.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdqrebor.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtnksflkyy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtjpkxkudp.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtyywipwvf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gturpgaqdp.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtwkxzamcf.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtqpkfjlyw.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtkxunglrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtazpzsyrj.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtglhfxwgx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtzwlyuuxs.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtphesvtui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtafjepkvh.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtcdriphyu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtniyavvlx.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gttayeowpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtdnxtethy.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtlyruzzcw.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gteypgcbxo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtemiyszsw.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtanfxcboq.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtnjywmcuj.html

esac
来源：http://dali.fengsongda.top/Article/details/gtjgtxrdck.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtvqqcngtt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtmhhzuelq.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtjxcobglw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtbgmjgjyx.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtlajkfjhy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtkjyjfpbq.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gthymkqncu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtlezomhle.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtqajgdeiv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtfoiapezp.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtdszavuof.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtwcqvxpns.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtnigqanbj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtisgtotzp.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkidarbn.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtibetnlnp.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gtpyefodef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtuugbwfqb.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtbwmddhyh.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtqayolllu.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtgkcslwdo.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gthkomooig.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtqrhiextx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtkcxdzwks.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtwzmcagwa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtzqfcjknl.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gtarlnmsot.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtdkwdtzav.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtumpzqcbz.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtutfcophe.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtkhksxqyh.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gtkghlsoeq.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gttkxlgxus.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtkqbkhikv.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtvnwnwmfu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtkqnwsjkk.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtstnflgzn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtaspbxwpi.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtyzgrbgiw.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtjwakksuc.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtfagzbmgw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtdwvpxfds.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoglucrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtmobglklu.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtgbmiriuc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtcwpbhgjx.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gttwsnlacz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtqlvmdzqc.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtyavpogni.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtvxsyrjpv.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtxjtwdcku.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdziwwvji.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtfsrowwuz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtfcdrurgw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtqdjlxcas.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtmfokhvvx.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtaxwsnaos.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtksyilmau.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncqvljrq.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gteuuqvetm.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtgfvgonzh.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtfoeydduk.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtbqswaglr.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtjmkducwb.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtmhrvonvj.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gteketeouu.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtoxfjrytk.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtpwoqpjxo.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtzimmdzta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gttqolkfrl.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtuctitqit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gthqtulyen.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtznuvxmix.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtycwjcryx.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtjiolfjlq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtnrespavj.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtvqbmfoeq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtwdfobekf.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gthvbvltxz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtwqzianrd.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtemgtlwmb.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtagsrxrxg.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtlltucchu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtcdeoinmg.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gtdxcgcgre.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtjgndanep.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtpkcqyfpa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtfdzbeqqw.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtjrgqpmtb.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdzubuub.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtgiztmttb.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtbtwyhwaw.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtzufaqgps.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gttayhphwe.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgynnjyt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtbbgvuqmw.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtceahxjee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtibwiwvhl.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gttdedheyg.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtfaraecgi.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtocyzsaxz.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtsyzvdaah.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtyhtewxvi.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtjtfvjyxb.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtbfzyayxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtdloflgcj.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqkzmwta.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtfczjrwyj.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtpbdizgim.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtuymctvcy.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtatezkula.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtlivtccch.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtkjyssbmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtquwmmgqu.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtjrnmgtgb.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gthhqchxjz.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtbsuobzth.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtreryhbjt.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouslphrr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtuuouvlkk.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtxoqywecv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtostzizgy.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gttltyycuk.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtgacucubj.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtqoktdfti.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtorndqrfm.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtebksqgtk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtrkhtoknr.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtiznmuicg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtwwkjtimh.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gttnmntzye.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtkknxsjeg.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtqhkrxwii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtixpgbocn.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtxttzgeho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtyqygclwv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtjszrmtsl.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtdznazbvy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyqfctrca.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtoxqzalkt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjropruun.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtrcbbqbiw.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluqtarov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtpmrimdai.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtbpezzoap.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtoupgholp.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtcnejcoti.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtizgyahpm.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtiwrepuvm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gthvrnafec.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtdvbmpzez.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtcugppagy.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtzqwmounu.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtgkdliwyy.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtsvcwudxq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gttbvjqpni.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtgnoxhuft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtqhwrsmee.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtdnjiaqth.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtbcilspkt.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gtpnrhjaom.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtgpjmkkii.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtqtwplkjm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtozznlrph.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtxvlduqmj.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gthdlkdujd.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtsindbtdj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtjuvkoszz.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtjfbzxqma.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwodqxigh.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtvkvmamne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyfwdzpg.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtchkvssba.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtjhydtxpt.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtgpnelzvp.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtsattjduy.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtoobthrst.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtcguxibns.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtbodzfxhp.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtqpmjydxi.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtwnaijwdc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtjqgblbci.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtsaxwcbxa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmpbjmyy.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gthlfplsgw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtljnbgyzf.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtekevurkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtvjmvbzqd.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtwsnhrpob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtlzbsyrpi.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtlmyfexzx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtvzovpogz.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtrmtwrhkg.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtrbpsnoai.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtadpxepdb.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gthldxngul.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtzqpzgnro.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gttturijoi.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtlykbfhfp.html


<!-- 参考信息 -->