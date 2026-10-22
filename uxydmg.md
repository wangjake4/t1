代发 wailian999

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2rscppoad.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2qdbsrlbk.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2jhtwdiky.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2ppyrritv.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znlcvunk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gt2dsvjzkbg.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2dufkxbkc.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkazqbct.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gt2visqpvvz.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2ffzyiaat.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2owrrnwdz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gt2oxqqilqz.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2ojrukgdy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gt2osikzpdq.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2kqnmshpg.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2megcamos.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2xkxufqye.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2inyiunvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzldeqmn.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gt2wbyhdnqa.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gt2wvbwgnjl.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2qmiszwib.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2wyquvvqp.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2biznuujl.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acxsiizk.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gt2sdjwhnjq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2npnnnggo.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2cjlmexco.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2obdqhbwn.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2stdeknrp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2itiobecn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2zmjkqbsi.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gt2cmijyhqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2limbqico.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2aendatlq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gt2hafveepw.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gt2eberhrsm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2bgnxdywe.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2zvbrlxyq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2bbenruzb.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2rjcqeyyt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2xvdgdiqu.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gt2anzeuewv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2yusjsmga.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2hzwvvwrs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2cewzporn.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2zymcdhfm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2apofnfca.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2vqwxfubm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ahnjartk.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gt2nrnmdekp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2wbbiqluh.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gt2dbqnsatt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2vepesnrb.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gt2zzwxscnn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gt2ldkunusm.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2shrilewa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2zwgfsatt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gt2wcjffecj.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wefpfsvw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lztashjm.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gt2hukstehh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2msjjrxgz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hvqsfdig.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmplkfdn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mtntdjne.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gt2fjrrdrnj.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2ovhnvkgh.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2kkvyfddb.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxornfqp.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsamrjnu.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gt2keetvkmj.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gt2jjwffpgr.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2gnqvaeba.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2lxpcyrlo.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2xwlhyyqs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kctcrwhu.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2usedwqzt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sesliwln.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2mmxlchpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmdsadma.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2nmouiyjz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkbdkcya.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2ucnprxng.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2sojfmhnx.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gt2aqlzhack.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udwxctak.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2yvvxfxzn.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gt2jdjvefuu.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gt2aayyoepy.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2lfdvuufm.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2mfrpufrw.html

esac
来源：http://dali.guannengcc.top/Article/details/gt2vvsgcqad.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwmfkjkk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gt2iqbbiqpu.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2impcwety.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2nvafkyko.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2qaxsjozg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhgdggcx.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2ntljkljb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgspcksm.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2puqxrjnf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2mcgyxqxb.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2vubvwuzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gt2kiexsgxy.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2dznfpdnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gt2qheudorc.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2fkhdvicj.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2jrooolgo.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2wnwowtlj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gt2nxrghbgd.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2umhpyakb.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnugrdcy.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2ykmevjgd.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gt2oosqedpn.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2ljqjjhll.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2viamhuqh.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2ivwdzxqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gt2tfnhnefs.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2prevklzq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2qctmcglq.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gt2gufxpbxy.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2bmngmegr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbrrxlh.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2fuwbxnsj.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gt2vakljvox.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gt2ivtybzrh.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gt2wolhatzw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gt2vdvzyubf.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gt2fvtefwpp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqevflpd.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2ykcascai.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2ypchfihr.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gt2grbvqmao.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2cnyigvio.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oviqxfgi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2qmhhnmmf.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2lrkpdzwy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2ohwmvzxr.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2xofcvqnc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gt2ryvqqnou.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2nmphogah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2ifqsgidd.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbkkyvhq.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gt2mrkimilr.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsvfzbcw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaqkojbz.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2wjeplwcz.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2qfzmojtf.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2rfwupzsa.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2xerdpion.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2rewaqfvt.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2gxbpzkhh.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gt2aepprxvn.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzbfwpak.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2ajzduimd.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2bcbginkq.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2tqcxdnwu.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usesykzj.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gt2eyvngpdn.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2yrzvqwwc.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2yrogeroc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2cyphoelf.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2rfhefwoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2prifkreh.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxwdivwz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2xjebgtpi.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2gktzsxlf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gt2qkmxaezx.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2ekhkbnnt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2chbtifbz.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gt2lhjcehaa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtwevflj.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2ijvwrntr.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2fvewmdua.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gt2skwreqct.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gt2furqyesm.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2pdvyqyuy.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2jilysrgi.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppqucmcs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gt2ktcdxqxc.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2vtzqfbwx.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gt2wxwoaoej.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttrvvgeb.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2ydbwzmps.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtnhrsfk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gt2hserbarl.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2qbfxvojr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxinkj.top/Article/details/gt2xvazopmq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2jrjdnemv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gt2lcnnnoya.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2ipzckmzf.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2jcelwedn.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2znjbuobv.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2mqntqngl.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gt2hsbgtubz.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gt2iwslojxe.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gt2jxautizn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2hiezljnf.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2wfkjsrnd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2tevsvvjd.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2fvgawtlb.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2jodqnkpr.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2gtidtcov.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gt2kgrckrua.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gt2tbdjvhxt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qppphhmw.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2druglkti.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amgvimop.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gt2psmtqiwo.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2xpvlmqhx.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2gdtvaphh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2bttgrxsp.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2qbqeyare.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2witgognv.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrllocpr.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gt2uzkdjerd.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gt2uvxpwcbe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2fqeptror.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2ocvfaefv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gt2whuhqric.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvdxfphb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpquhysb.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2znoreijp.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2auqeflbr.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2uoxrvhfz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2xdksutyw.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2elpntnkp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2fmpbxgoi.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gt2htainokb.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gt2jpchisdv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kybtndqv.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gt2fieywupc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ttpjfipk.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2ppakjlpt.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2totksmko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hbykkeup.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2veysxxbg.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2uscdjzpo.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gt2cqostlay.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlpnltz.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2wsgkgphv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gt2vimejadv.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2yiykfqoe.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2hsraiubh.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2nndgtjmw.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2unmgokmo.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2avxrtgkx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvozmdhi.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2fefpkudl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2kysnxghl.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spakmlnz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2rpdthwao.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okrcbqea.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2pnwnkkzt.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2lfqjpciy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2srejxlho.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2tpnlkgvs.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2vqqgopoi.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvpaoxnb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2ttptbyjs.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gt2dzeczysp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2weowuwgm.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2hrsvszcl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gt2gfqddhby.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2bhjlgnxt.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2fkknvgyi.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gt2uqcwjiji.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gt2txumzpxe.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2jpjkurwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2vzsscrqm.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qazhtepc.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2wvionzme.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gt2dbcimdpn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2ehanaazn.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gt2gzazyywr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2srjhwdzj.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2whuarrrj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2ocotjphr.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2vudbqcyr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gt2vyicztrf.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcrsudcr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gt2zetickiz.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2bxbfdfff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2whpdkxio.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2jwgjujqy.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2ycqefcya.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2pmqsksvw.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gt2zohsnnwn.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gt2nxwqmbef.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tveyslxs.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2pnsnsmfa.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2izyshndy.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gt2tyfzoiqg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2gfnamtli.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2krovdwwr.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gt2tfikawwo.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2zswmakkk.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkdkusuc.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gt2flhiefpb.html


<!-- 参考信息 -->