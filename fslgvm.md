代发 wailian999

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2clfgrkkh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gt2pjerhqqm.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2tosnhjxa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gt2emgllkqj.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2umjuuymn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gt2rubislvy.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2mvedohpz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gt2ribexkkz.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gt2jzcamlqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2dxeozkxs.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udmjynwd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2eylvajwv.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2tkyudzux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2dccphpjq.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2hqxsbvky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2wagxhkqf.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2qwvtaspk.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2yanlorcu.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2vkolqshk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gt2cwhuophz.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gt2mhxbkbty.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2luihurjv.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2abfwwuif.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gt2phydqmmj.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2umiiratf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhkrirqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wmvvndto.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2lundkixd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2tnqxrmtu.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gt2cprwxpzb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2qtkgmyzf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mdeijqov.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2ytmpgyte.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2zfnlrpos.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2rslpqtvo.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2qsikwgll.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2crigiigi.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2nhnuzmio.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gt2lnjecjma.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgnofckk.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnajocpt.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2lhadiham.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odooykob.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gt2cvmyohcf.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2bwcdqmyy.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2jdwdjfuh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zkszhrqt.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2sjwodvbb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2vllwpsll.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2gvasvgws.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gt2umlasmvm.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2vntxbdit.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gt2zjvqzrnh.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfadvavy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gatlhhbn.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2nshbrwhz.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gt2ughsgxvd.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gt2hvlbwrir.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipprkhbr.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2nkglxbfc.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyxuiysp.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gt2hgkexofm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2quwbsnza.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2xgnljopt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2doifluhn.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2ylixwwzc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gt2qzyzwnrb.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2hmnxyahb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2jptjoszh.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2hfgefmrk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2cmpfcxiu.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gt2wwdrqopd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gt2aoqdtbty.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2ngcvowyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gt2prrtwatt.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2opfcbyus.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gt2oewdvvte.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gt2ijxscfht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2vvwmjkix.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2makgmwuh.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2bvpapkbq.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2qonwpnzl.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gt2mexqzgpr.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2ajmurjae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2mfvgkron.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2omvjqehm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2yzanvdvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2htswimiz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gt2oingeepd.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2hdicpszo.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2giuvzjdf.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2nhfeyrgz.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gt2vmwmzfwa.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2qqhaoldj.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2ojijxpsr.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2mxduukak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gt2grqearhd.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gt2befapkmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gt2lfenqvzh.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2yjyfqxju.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntqlhpqn.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gt2hlfaoimk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2mckhvwux.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csrmniye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gt2pcrdkret.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gt2bdrdziff.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2jaewdhug.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nemdbliy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2qzhndaso.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2lbaxznto.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2zqufjwje.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2elkzfsoh.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2lweceffy.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2ppsukewt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gt2afpqmmxg.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gt2scrltsig.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2qtbjswpj.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2wwsdwsdu.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gt2uluvstvi.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2lnuqxulz.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2ntrqnras.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2fgshqggf.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2dsakapoy.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2txyofwno.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaczfamg.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gt2maeuxnul.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2hrkxckta.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2pvqjkgfr.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzvfhmpi.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2wuusdehu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gt2ssriwbbm.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gt2ydvqzdsg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gt2jmgfibdk.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2okozryow.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2xkchgwhe.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2bpywyxxk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gt2jeupfpwk.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gt2lfcuftxu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2iyxaymxe.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gt2nxilyyde.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2dqjvagnk.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2fjgsnxni.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2yeofroay.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfarsook.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnmpjhbq.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2ewptmibv.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2roxuxgjz.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2dnvzburo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2ahlpedti.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwsgmycx.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2ajrveigl.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gt2mvzrjsnf.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2pwwvjyfg.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2xshvckrp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2xqmtgiqg.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrmejrfl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2uchmfqay.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2jfsscwaw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2cigtncbk.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gt2ramhwjhn.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gt2furzfnws.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2jrzdpfcp.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgzhzbdp.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2zocxzslr.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gt2esxocnec.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gt2qpxdcksx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2gnidmwdh.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2bfmniuyn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gt2apvbcjil.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2izyvmbdn.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2umjifpog.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gt2luzapxnt.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2hckrpnwa.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2fpiybuki.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2kfqkunty.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2nlqgpuvx.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gt2jpmjrlyl.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmlvodxu.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2gruqmitq.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2mkuvywml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2wjtogsru.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gt2yvvjlorx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2srizbncc.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2vuhzekrj.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2uvdcshht.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gt2tjbocuzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2tvekogcp.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjmjcsxs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2lworwxsu.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gt2mrfbdeds.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2lvzfjtyf.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gt2osuwclca.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2uehfblwj.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2vplfzbcp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2bhbiatqe.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gt2xqjfgath.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2jsiahgie.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2swrorrqx.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gt2putffjnb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2mpzwjaks.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phqcbcva.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mimibxms.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2afobrtrn.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2rypoargy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gt2norqxlhc.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2nbbuieqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2pjazahfh.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2zpvqlcbp.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2spsmoydr.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2pzazqtph.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2otfjumwc.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2gmtzlyou.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2xqnwmiwz.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2ijoxzxie.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2dsosxwyz.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gt2cayxmfrr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2caauceyd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2ddaieddq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2ysfwermq.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2foqnnsmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkoirnde.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brfhphbw.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2dpljffwl.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2yseksbof.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2kevbpsmh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rukegqog.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2pmjftfal.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gt2tbnmbwtu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2ikwwvqzr.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gt2svczeqgk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2qhnhffpq.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2kokrgtlb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuwofphe.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkmuxovr.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gt2bctzhvsb.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2ckvjbzby.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gt2miiyvycf.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2lldaglhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gt2oerpyxck.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2mddvngve.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2qjvlyufz.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2snndywvm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2kpufenls.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2tcyojnke.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2weoaxvop.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2oigmqleg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2zgvqscgt.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2wvfwscvr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2ltcyjkmo.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2fpwlcrxu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfjhhnkx.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2werhrhjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2mctrjasc.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2opkvylnk.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffeejkuo.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2vxboevlr.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gt2srxzqgud.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2rdabgypr.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2hxmgzytm.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gt2nytnriyq.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gt2sjtyppnn.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gt2djsxkrib.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gt2hdujgfxb.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2gxbldomv.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2hivmbkve.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gt2fyiqockw.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gt2bhgzqabn.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2kfryqwck.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkgsklll.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2ryrbqdwk.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2valhbjzv.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gt2fovekgux.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gt2ydohjyuu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2qcgbnuyb.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daszdgzr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gt2zwmiyxzz.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gt2wsivufcf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2bhqnlnjp.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gt2xlwsrrvp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2lohryemb.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2khdbcicg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gt2aitthzce.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2itiqxlsr.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2ieaotuyx.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ratojwmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwibakor.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2yxscxwen.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfmnhuxi.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2gvsndgqt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2kkslogyj.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gt2gepxtlzi.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2jzykqmwz.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2qfaayyha.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gt2yqjuorov.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsgahch.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gt2ddwlyflo.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2bxildzrh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpfccmtx.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoqyuflr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2cremnpsm.html


<!-- 参考信息 -->