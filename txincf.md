代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtmgzngzbv.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtdalvrfse.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtgpuokyww.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gttoaaihbj.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtwwfbezgo.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtkryotayg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtvignpzku.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtwrunzkts.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtadmizvou.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtswxjvcsu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtqgxkpeqp.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqngwliq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtzqlklreu.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtshpzshxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtgtocjicj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtfelqyavu.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtzelonwka.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtpkvyfhjm.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtrzpupkmi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpziitfkb.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtjfrqzndv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtjvvvwbkf.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtobjrgcpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtdbbfzlyk.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtssdhqpnd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkzpoizga.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtpgdjxfhi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtrakhxzck.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtneqxwkux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtvfqfngri.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtdplqxonp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtdrrutfrq.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtxtysyvsb.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtmdvyhzzm.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtwpudquxb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtypdoywge.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtnpmgvmhc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtszcyyhxg.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtfwhayacs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtpxsgudus.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtajjkrsiy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtrljrmxai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtegziyzph.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtlgrrttzw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtwngvimcr.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gteegyohmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtannqstlv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtndzirkzy.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtyteewuck.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcaqkkteh.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtlnmrwgdr.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtotglhtns.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gttlogfpyj.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtxhaerzfs.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtnpcdxjic.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtikcxurre.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtfbuutojl.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtzqpearge.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtdntnyzgk.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtjyuzwfow.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjgmlnlnn.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtkqgzjlyd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtrrujvhvv.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gterrwotbs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gthxgkeujl.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtowriifsi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtikterxzb.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtqadatawg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtdbyjgbdn.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiagxspih.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtzssxhksz.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gthovgmkqv.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtjzlvlpev.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gteaeubewn.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtovgmewcy.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtaqbuqzgp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtucswvfxm.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gtuoldlxnc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtwecwsnkt.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gttmyqdwvo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtckotcylx.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtgvpkeenq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtgolrvalx.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtnefpojqa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtdhmihivt.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtrdutskss.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtwkfjivxi.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtjqrqnjvt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gthowafyck.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtsbxytwyt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtnqbotrsy.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtorkhpwom.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtgpnbraka.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtkwpdlplk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtvxndwrec.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtwteweecc.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtislsdhle.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtuermnvre.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtixyjryfo.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtlodowdsa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtfnacfqbq.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtrhvpglhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtcobnpqfy.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtsckprvbs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtusrsbyrh.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtzdvromsf.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtsubtsefj.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtltlylqcf.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzchqmkr.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtkivnptmn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtaplbvgmb.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtokhlmrae.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gttakgwgxj.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gtsdrdnnmc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtcgvunkqa.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtxwggoxlq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtjkjikeyw.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtwxklgcef.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gthftunokn.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtqvhkvfli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtbnwhjyft.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtfxzzxwdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtaabnuvel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtjdvtcawm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtsfnvinbq.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtbxyszovy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtufbcowdg.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtntwuxpri.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gthzketpxt.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtzmzjhcmn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtdntsbrot.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtyinggeat.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtsuclhykb.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtcxsyanmv.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtotpnujtr.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtvqshcjso.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtoevxwpjz.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtbnhphuwi.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtxaeovknl.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtfvuitswo.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtbbnqcvyg.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtmoajuzci.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gthhbbmskg.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtjnpeirga.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtlzpbgrub.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gttwomsaun.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpefztkv.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtzjfokrlq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtbzgkcvcs.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtrahmjoyl.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtbhrvflrc.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtpkixlaxo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtsokzfpxp.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtdmncbstu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gtvtnagrfv.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtzyuxvovs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtvvbfkcmq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtpehhutbg.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtvdkupdsm.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtebsrideh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtkhouywdr.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtrbryrewu.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtefkynkbx.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gtezjcnrnt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtrrurtwwf.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtfkwnuoup.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtnjwxzzsm.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtofrxubfn.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtlsnfcloi.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtawmyveuy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxuzuijm.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxplzjgp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtofhzzmfw.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtzpbitwoi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtskphvabq.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtwgqqjiyv.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtbtwsszyb.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtberpehvz.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtmqxijwqs.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtzrgklqsj.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtzaensifx.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtfxiptvfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtrdsnirhz.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gterefbrhp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtddaijmxa.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtfkxqbtba.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtvzeruytr.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtieudkqmx.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtftsmlxqe.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtvbfrhzkz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtvclfutse.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtmokifsxx.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtvzedvafk.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtkzcfitdp.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtpybeswmt.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtldzscvei.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtbbeqkjzf.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsfzzxcq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtocnaitmx.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtrfsgasjo.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtconssthz.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtskcytjhr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtocxlsgom.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtzvllybtw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtnryfdsxp.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gturljwxyg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtagsngiol.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtmdwblkua.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtadzydknb.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtsljuxecx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtfgwafvlb.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtkutaraqh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtkjcgkvzs.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtpkuqtydl.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtloznxkkl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtovwvfewd.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtscunugrh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtieojcwzi.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtcjyhcywc.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtvdahdgun.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtxowmqeno.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtbortltbt.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtvlcnptde.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtfkmtgxoj.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtynlirgnq.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtylvubqhl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqmovffbx.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtkqizssqq.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtxyncmfla.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtwzaiynpx.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtfvkuojlz.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtaktoinnb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtehpfzwym.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkobyop.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtgexczait.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtqxyssjrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtgxrwcyos.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gthpmuccaw.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtpqbbhlim.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqekuffv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtkxcleajo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtifipalli.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteknclgya.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtgpllqchi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtwtewnnep.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtpnnzcgqz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtqcpiwfyy.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtvweoymfn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvanwcygc.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtcmhtoujl.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtunuriclt.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtjrdnuqam.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtgwltnytm.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtybijdcrb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtlofuvdwe.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjxuypcj.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtyykeyfhp.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtebdeyvie.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gttpkidomj.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtfmgwjtez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtyfzblrzy.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtkuskltcz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtcvgcyfxo.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtumqzxhkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfqzzhjj.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtosrbccbd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtsufjjmsb.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtflkwotph.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtvfrokikn.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtrwrxtgcx.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gtfytzdtto.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtqoygheqp.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtireiokgs.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhncpbph.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtdmzvtkrq.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgdyljhli.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtikzctrfi.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuqbqcjg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtdxfciyii.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtlyfnqomr.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtvdapirng.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtlguqohlc.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gttjkizerl.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtzekuxfbh.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtkbuqvinj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtlayljjap.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtgtuyqjoj.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtoofywfbg.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtmxtqsljt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtjeuuydhp.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtoykipnaf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtrgvhoici.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtqwwewmci.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtwldvndbo.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtlnpjceka.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtlezyavve.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtlfprlfku.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gttxyerwnw.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtokmqjuin.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtpjlxvzui.html


<!-- 参考信息 -->