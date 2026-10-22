代发 wailian999

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gt2umgwpsuv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gt2ylvszsvr.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcumxveh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2gafeubag.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gt2bfxxceco.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2vikfwaow.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2aimuoqzn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gt2mjfprjxn.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2jpnrsevo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2mzhtlthk.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2enmjtgzy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2cjsgotvw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbefvzvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2khiewxbt.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2eopwxknv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2emereewy.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2frovbbal.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2rlcywyuh.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gt2pcgxxxbw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2ocpfspmk.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gt2kwuivukx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tianlin.xyz/Article/details/gt2hhdkcfob.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aavfypfy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2jnybwzks.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2wzwwdnsv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2iedsrkmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jraeuiwr.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2wgywotof.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2oozkgbqm.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gt2ilvjqhcz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2zckwtesp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2eugqugwx.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2uerrhbrq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cpygihuh.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2pggswexr.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2nvpgcqrm.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gt2tqwdpkql.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gt2zwgosqkq.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2vupqgshw.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gt2dowylbsa.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2hpjgbeot.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2kurmmsak.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2cainhuib.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2lrcvtvwf.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmjcujjy.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gt2lblaofbw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2nwnewlzn.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gt2pnwbwfgb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2niuirvoo.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2lhgcejsb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkhiiseq.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2dhvhwzwi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gt2drxnswmq.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2ewxbmyor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abegbgqn.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gt2vrhvuxxa.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2zlldpdpn.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2eksvvadu.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2tgskzdyj.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2dyanmozy.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2furkmkez.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2zetrftrr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gt2adizjgpn.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2tqpadbqo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2dbfnpgjg.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2sifxqsmz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2wpyyeypp.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2aohrctwi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2hkrkfomk.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2nvrduose.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gt2eqmfsesh.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2sanwntgs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2irkodqha.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2qazcvvxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufbjseri.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2rbyxcoak.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2eoxhubjo.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gt2uxbubflx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2yigyrypv.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2sghhdnzg.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2unulkuwu.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecsabyqc.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gt2dloibnyq.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2wppryqii.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gt2qmqhtnzr.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2tkqlssrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlbrxxmi.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2hphpdgmw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gt2mmmnowbu.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2spmpmrai.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2cuzyaldj.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gt2zgaljftb.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbsflxvf.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gt2ktpifjhk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gt2fotauuqc.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2jlaoutto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ptkiyfku.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gt2exuhwwcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgwefvle.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2trrzhxae.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2uqqcbift.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2jhmsaiiu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvargssz.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gt2tbipbmeh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gt2gajjpyhs.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2wbqpgmvh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsvmxief.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2hymnhmmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2grlrflcj.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohzfkuln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gt2uprriawr.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gt2ohjfyzfw.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfszamwu.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gt2aazbevfx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2hsultsum.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2pbxtldrb.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2mrxpdfng.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gt2kuxyroim.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoqgrjx.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2pmjecnmr.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2njbavfym.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2rruphiye.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2txmcgiya.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ugwujphi.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gt2wgwtjnsy.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2tturwjzz.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2jvtmxfze.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gt2xbxhksah.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2ygmkovjx.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gt2ifvxeeik.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubsjbnoo.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gt2xketrbwz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2ojgcdvbp.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gt2vzcymsnq.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2ejlfcflb.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcmadlwy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2iooawzqp.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2mbgiyygl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2pvojuvcr.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gt2lkgqrwhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypisubpc.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gt2oreotaiv.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gt2cmirjire.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2vlghexye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2aekysdrg.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2lypkcdjn.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gt2bdsubgne.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2bngoxslj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gt2sbynyjux.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2znynimdj.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2dseekxjb.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2svqyjjjt.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwqclauf.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2fhmyscsy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gt2tnrnjgqv.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2lmraoxoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gt2xbginloq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2bfksvdum.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gt2cprdmmmp.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2vmdkbwwy.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2opwissow.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2svdbfhnr.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjqgqpmy.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2whuigtdg.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gt2yygslsdc.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2khjwhlsj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2icftwjcj.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2uizswubv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2vsspcldw.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2eoxsjgpi.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gt2ucuelido.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2nooqrtvm.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gt2adfaiakv.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2emdasatb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2gojyfqjw.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2vgjtwhym.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gt2ocglixku.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gt2duqkmyww.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gt2rjuhwxxx.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2ftqvjzfz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2itibandb.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2nkdrygjk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2ybdmiijr.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2cqsesaau.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gt2omgtfmnf.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2ynrzllfs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdyfpae.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrbitkgd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2suwkqzbf.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2hnpslaym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2muvyrabr.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2xqqfqizu.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gt2evysshja.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2nqakhhut.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gt2oolyerqy.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2ygnmlrfo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2pjsrxajw.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2isdpkzgw.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlozagrv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zabtbxns.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2tkxrogea.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qjviekmz.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2uzdzfxlu.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gt2pvobvacn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gt2bysgpagq.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2nodhyqhg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2ureuxteo.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gt2zmqvhdkv.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2gilesdos.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gt2rpjeswpu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2xhrgrnuo.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2qeczmigo.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gt2sutvazat.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2urbyxcys.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gt2jebnksni.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gt2dlkqmpji.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2bxhzgimr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gt2wbezalxq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2avbntsit.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2jfvjpbpa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2lzfrldvg.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehrvdtoo.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2zuujswff.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iecqknne.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2fxzdlvxg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2duoppykk.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2mjogbjsp.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gt2einrocif.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whnkzpxv.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gt2ulitkyyy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2pmvgtvbr.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2ljbxcffl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbrpkamk.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2caznzmli.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2pkirvita.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gt2rlbfpiwu.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2osfasazw.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2xtwmqjdc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2hgoazdey.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2unkdqosj.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2hrpmvmbl.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcpebous.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2gbeozqgc.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2akgdbzpo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2winhoxkq.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2zjurefdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysjmyvhk.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gt2sezanmiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2pdcmawvm.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2iwwhkkbi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2sgcdcexl.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2tclfxxyt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gt2nfcojkbg.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gt2kbiwimue.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2csrdibhe.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zffoyvxb.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2jtjrlcdg.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gt2xmbjdxvw.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2pwmdwdii.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2gqjrnyys.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gt2ylqdtbgc.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqvzqfss.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gt2mesitnwd.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2kwdstlas.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yraeiyzn.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmkqtqfq.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gt2akvbpzos.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2nmmuqjtr.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2bcjypumc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faeuhwdp.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfyoddjt.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gt2cieuxfub.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gt2urdticwt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psxkrbgt.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2fswvpvkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2ucislplb.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2ksairphr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2kjukhazl.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2miwyntsu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2habwsmgw.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gt2jhmdmbwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gt2wmshnwgn.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gt2mnjslbdn.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2mazfxmia.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxdlwlgn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gt2kbcizalk.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2oufxszgm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2mlnpnktv.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2iscbebqm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzpfzhpr.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2madcjdzb.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2dymcslww.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gt2pjyamgrf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2vpeirwjp.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqwqcowz.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gt2zsnzhbci.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gt2yideudke.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gt2xpbwfqdg.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2cxuhzibd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gt2fneqpwys.html


<!-- 参考信息 -->