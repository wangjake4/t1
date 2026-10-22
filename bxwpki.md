代发 wailian999

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gt2eikitppt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmzvdlh.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gt2gxgaygpj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2dabhqeuo.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2srvejgsm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gt2pwxpywhw.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gt2hsoyhbxz.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2lohtyunx.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gt2wrutdkba.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gt2hzdzbsat.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2mqxxslsf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2sjaajaok.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2sjmpsmbw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgekgirp.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2togmxvdh.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2ulgbbvfa.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gt2yvtgrgeg.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gt2appoatht.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2uciiaeov.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2hazzvnzu.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2envdfivk.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2lebigkys.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gt2cegttiri.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuyeked.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gt2fswltepf.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2ijxpsisf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2xqrqqrys.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gt2jmkmksag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2bqrgudqp.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2nnzzzgcm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2cwqdmifh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2rliksngy.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2vwpwmrgf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2rmkfslky.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2ayshlpbx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptfsulbf.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2fdpnieqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2bqvdqjje.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2qvegbeyw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2tmhwwtfd.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gt2jmiylgav.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mbkojarr.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2ualewyjh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2exoczmss.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2mywrudgx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wejbpdet.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gltsohkd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2thbxginz.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2ynludcxd.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2uvvzqlui.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2mqfutmfa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gt2jligwjva.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2ifqhtmgw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gt2gsvhopvh.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2kmuenvbn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gt2fidsbopq.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2zdmbngfl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2opdqpscv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2fnyiigsc.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2bozmqpga.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2ekrdxeyy.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2ntumutrk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2ekkhwiqg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kkbqhnbv.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2ktkbbfuk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mkmqdxps.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gt2jcguoail.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfkcffkg.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2hotzwufb.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gt2etknqoxo.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2lpjqvkuw.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2phowhexw.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gt2bubgsdgm.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2xeufbvjs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2tvcfupen.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gt2azpiahcd.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2yvruzktz.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gt2kdajwqeq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gt2vsfgzhyu.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gt2qukheidk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2kscxxmbh.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gt2jpaxqrud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2jejwkyjn.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2vbqsfgyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2rfbvyrfj.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gt2lfdfjxuj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2usyppsee.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhaxwpiu.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2dpmoojew.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gt2ykuabnkn.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2motmdjtk.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gt2kcxqaksb.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2zbpedajv.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2bfjdlsyx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2xxozuaxd.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gt2dkxslyoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2gisznxbb.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gt2qmlgugtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2jfocpbmf.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2ixznzcoq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2ouqepkkl.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2xjpmudrp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2wmaqesij.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2azguhqys.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhbsntft.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gt2ngqwpvqp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2vwbxfuzi.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2khfhyppz.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2vkdqpign.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2szxpecjz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2nvrpsmyr.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2wilplmla.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gt2tjmeedlb.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2vszkoazp.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gt2gzlhcncq.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2kpmhcthg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2fjlysgqb.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2xkedgzug.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gt2wnljomak.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2uxrydcen.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gt2rqmmoojb.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmalluab.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2xkfymaol.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2mhztucfn.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2yosxtcsd.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2heejulii.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llvzihqc.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2eotyurkt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2rhxokgmk.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjyecixq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2ibcivdgn.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2kvformjf.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2rmoiounh.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzikdemd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2rzmirlvs.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gt2xmahrqkh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2ezddrshf.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gt2snuxzecq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2ixcenmkp.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2jmbxurpm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gt2foopfvdb.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2vkkxvkrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gt2gqvuzcqy.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gt2lvutwlnk.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2pxdpsasw.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2tdcruvcb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywypijap.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2ccnjdvaa.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lamhzang.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2kzdbazit.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2zybkbsnp.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpkdbnxo.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2ygvsmphk.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gt2roubivww.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2wiynwmnv.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gt2pjucvcjj.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2iaeunqpb.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypmehbxj.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2dgsvwqcn.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2dicckoav.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2kiddoeqw.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptwlargs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2lbwpxgtd.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gt2laqyrcux.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2okilhodn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlzbmfw.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2emifvkcp.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2zeotgszw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2gpnnhota.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gt2uxltmknc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2igzennxp.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2psqtzxom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2takbycil.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2cwftgoll.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2wqfpxdtm.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gt2ubocffxb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcykfmxz.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gt2vobuwkkt.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrfhyvww.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gt2oozfrhcy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2ogturbdr.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2dqiprjqo.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2pmgsxwzk.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2otsuwzvd.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gt2scykyjfj.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gt2mqtggtnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2pjrijeym.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2xpmfxiar.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2avmlbmku.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2ryjwqfzq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gt2lywplqan.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwcxihsn.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2mddyhutb.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2fzioqdpe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2trbmmydw.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gt2adxsddjz.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2khcmmvfn.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2rgyutevd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gt2ebwpedvk.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2rsbrkqxj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gt2xvqeevzr.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2afmnbrvy.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzzqzqlw.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2qzfwkrbl.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2bhxaqavw.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2viwllmwu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ganibxed.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2ylxjlwpc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2bzalquqv.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gt2wjvieuld.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2lcisejtc.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2asqehcpd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwdugoeu.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jloqewzl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2efprzbgm.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gt2jawvybtl.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2fhhumcmy.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttihaeka.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2naozlwhg.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2epiowdzo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkxifqau.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gt2ruqyhcuo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2unppsyoz.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2thkmhkuq.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gt2eriybxwf.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2yahxplvs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gt2kmgcqafh.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gt2imhrqtud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gt2ajidoikx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaaquei.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2srixaway.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2eojqcznl.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2razbpvac.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2sdzakkwt.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2zvyyhpiq.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gt2gsnbrhfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2ejumhtco.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2veomekkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2jkesibbk.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2yhnrarop.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gt2moqglgov.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2upiuxpto.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gt2xemcrhbu.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2qbviddzk.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ghaoztdu.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2inimirnd.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2inyiiyaf.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gt2qsrgygjf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gt2lhfgfkrp.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gt2fdwxrdcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2cipwmlpe.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gt2rxpuihvn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2fdbagwwt.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2qnphbyvu.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkvocbkj.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2ydcknxrr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2vaforway.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwedfzit.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2bpljuilg.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2oohzxcph.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2eezxnabz.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gt2maygmfnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2nmjbgnji.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gt2pzdvijel.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2ydhxwepj.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2ulrpbexy.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gt2ckkjcsnn.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2fnpvqtiv.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2cmphpmhw.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2svysvytn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2zgcquzeg.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2ycriacuz.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2dbrlmtmp.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gt2nnlzxicj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubtrpsxa.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gt2maznhdoh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2xcbpahzz.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfhcadty.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2jnsohtxc.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2thmggxyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwccoqsb.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2rdujmxcv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2cgkfeldv.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gt2epkjabac.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2qyobzgwn.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2rhifuuxm.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gt2hngomopi.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gt2ilkeczjl.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2cpwwvvhp.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2lxdzrkfq.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqudwnus.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxwrfzrp.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2iqeqwfkm.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2mopmelil.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gt2kvkylmux.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwhtvtbt.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2rymyycxc.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2llazwfll.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2ziamsftc.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2byplsgyq.html


<!-- 参考信息 -->