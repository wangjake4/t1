代发 wailian999

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtwwywlwnw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtrxsyasyc.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtmgisggaw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gttjxbuysi.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtiupwwlcr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtgeaozcqo.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtfrsvaufp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtoyufhzcj.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtdjtaqbqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtrtcuztnu.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtuxxsyfdx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrqylvbto.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtbzblblaw.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtapfgkiov.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gteifurovs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtrjfrcxba.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gthxqodepc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtefmjqcgi.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtmifduied.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gtbzmrmuwg.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtvgjlpxnj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtjgokpamf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtktnutrzv.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtqmfwcykd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtswvgzkij.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtfyztpkkm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtnkmjdjob.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxnxzhbkv.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtxigknqrt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjmunrexr.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtyxfqnijc.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtquduyfil.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtxgqeyxsv.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtemqnmwti.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtkntdlyqo.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtnkdbhmpk.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gterwqaymn.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtvtxwcgjq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtcmyfrmvc.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtougpxrdy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtwbpccbxp.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtulqqvlmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtmnfdulte.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtsokkbhkl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtbwetdnuf.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtmtzjuyjf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtcpynrlpq.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlxlmkzl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtpwhhqyad.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtjzupiibf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtaqnidnin.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtmnbitckd.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtefdrrxbi.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtpnxwrwhr.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gttytyfkmi.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtlejcfjly.html

esac
来源：http://dali.yueranfly.top/Article/details/gttxiefyzu.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtwomrjsju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtqlbcncvu.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwurafnle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtqwkwxxuk.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gthpcbpdwi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtlmybzcad.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtucuxicil.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtilisuxfy.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtuliszmdf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtzoijgrhw.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtspaqwnhx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtnbuzmkje.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtxldwvltu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtlubnlzrc.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtbqczgwdx.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtuhcesibm.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtanmywylg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtugkwwkma.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtpnscnhgo.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtysgulcwz.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtkbsjlmta.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtmdbvjpax.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gttjabbcpd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtlnrqbwry.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtvivsxqku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtesowtwqk.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtqwwbebij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtgxvcjqqv.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gteduxcjtb.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtizpkquio.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtquqzothi.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtaotqawoi.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtlsspznje.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtvjvwrwgr.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmhlxcuy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtihzhemfm.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtvgtflzkx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtsmazeyxb.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtdiitshdh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtrvoajuoo.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtazyknlpm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtmgxhmnpn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtvdfxauwt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtmsqzpkqf.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtodtzxksh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtclhzfcfy.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtrhiacvkr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtqvcxjbqt.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtfdtjbdzz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtjtevihik.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtoewgrxvr.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtysdhuaei.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtkvevytqb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gttwzftfdb.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtqzrlhvly.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtdxqincsa.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnagyhwe.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtegcrejub.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gthbyhefve.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gttvwbkchf.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtmfbwhmog.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtnyjxuzfk.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnngkfsjp.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtgmuevqxt.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtorisvkrg.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gtvcxrqaoy.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtktumoyrt.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtdxrqyakv.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtvynoajgh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gteiylkcnt.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtyuezzthr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtdkgytgux.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtoqiswyvh.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtvdurcxvz.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtvjjnonwk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gtqoegiynp.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtibrbfhwp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtvwvqankn.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtumorjesk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtryhiezdq.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtbobbmyes.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfhpnhojf.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gthefqwawv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtkfdtmkcr.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtvxqhzerd.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtxtquaqnj.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtxxhefjvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtsqsjxdkp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtajxddbex.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtfyxhbqbf.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtgsihfzbf.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtpirdrvbm.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtlwudwzgf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtmthptopa.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtaagfpbns.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtksnqhwxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtabiftruw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtcvkswueh.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtzwocuozk.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtcmxbuwzc.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtdhhepbhf.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtpblvzcve.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtidocavwq.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtqcbzbboy.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtqsawoqke.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtibvepdhn.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtmfmuwile.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpejklmb.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhpyxmfw.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtlxtdrhkx.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtavxenoac.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtzyucbvxf.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtfnxuqtnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtucsaeolk.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtglvojwhb.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtryitqvit.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gthgrdpatv.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtddhbwvbc.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtmqsetbkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtrhhqfiop.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtnktfyqbu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gteanpbjms.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtiooacgkp.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtsrhwbfod.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtdzygwqrv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gthejwhaqo.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gthatdeviw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtrahzixca.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjspflph.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtlaygofme.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtcmopztoh.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtvyfyohpg.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtgahcujad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtfiwbkkvf.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdvnrvsy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtpgvqlhll.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtbypyvqnm.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtxrknekjy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaxdvesml.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtzvdrudfv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqotheulk.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtfmbuxlql.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtecgwzswt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtrzerouat.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtfsrfqupm.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtenzhyflj.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtbbjjkxvl.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gttvsxuptz.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtvrnlijtf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtnouvserx.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtqzrqailf.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtynqatedx.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtqgfyklua.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtmtojsvqo.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtlszbjlyi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtgqsrpmmz.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtaksrefol.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtojzzjzcd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtpnflkkbp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtiaskesbk.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtseeisrad.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gthjwftllz.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtogmmuush.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtimwqsylc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtjllnqzxo.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtrsrzwmqe.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsvvljtrz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtiueuugsd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtzgtecoih.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtwgsppmlt.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtbrfkyfwv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtbqptavas.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtwqoehhue.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtuuaqiwqb.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtvyyeroqh.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtppzfizhf.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzvhlavnq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtsehcgrow.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtmjnjukqh.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gtxfhofnmn.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtgkgudeqa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtkkznvspr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtjbqssxyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtlsfujjds.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtpbnibfso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaniddzui.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtnfedcvgm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtdeyzomae.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtgsqomljv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtzljdjmwp.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtyiyejqwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gthwovirvz.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtfnwduizg.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtjpvkjimw.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtwflxygcr.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtcsgqza.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtucixqngo.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtwlaiklmr.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtrdnbhluz.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtituufmqz.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtqebcsnil.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtqdpexxfv.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtfzwaqisz.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtwvyztcco.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtiepamhnq.html

#endif
来源：http://dali.cheryme.top/Article/details/gttqvselhn.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtcrpblsvc.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvrlytjw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtwxrwalzp.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtpqskahqw.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtnayugzni.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtdrmtyrla.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtbjpptfoq.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtqsookhpn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtlzcphuiu.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtlqmocvfp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtpoeiwikr.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtszcqreaz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtjeirbntk.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtgbpezvna.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtgbuzrvcf.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtmcgwkevh.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtyfzrrhtx.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtgxhihgtr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtaamffbxt.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtawbllvgm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpcpowqq.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtcvwmgrow.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtqpfuntwh.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtjtyghhqz.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtqrmbyxix.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtijpzsoby.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtchkoiktx.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtidijrcdt.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtzlwpkoya.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtbeqhlilf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtuelrregk.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtutesatgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtimwslmki.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtmnvasdsk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtkxfbdawf.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtmkwlmdxm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtsizctgyq.html


<!-- 参考信息 -->