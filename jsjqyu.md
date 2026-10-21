代发 wailian999

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtlvocrcuj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtnuyeojmo.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gttivpbrpk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtckphtrrd.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtqzzjyqgr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtdxstdeog.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gteslvwmfg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtoaeszamt.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gthctqwcil.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtppreiroj.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtzgdcpsir.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtryrlzivc.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtqhuojgki.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtukbhyrxk.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtqswyoefe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtxbupxuet.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtcxalgkqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gterodyonw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtuwlewoln.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtjanunqwv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtuiixezei.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtwroxvofq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtckzqqteg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxmegmnhg.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtjiubfmhb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxhfnatja.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtcskhzbws.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtdnodkqhf.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtujmivteb.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtfavtfaci.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtzsjqjyej.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtkffbtxzu.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtqfnknhoc.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtrbcvigfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtuwtibnmc.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtktyuofsm.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgoodsqd.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtjdutmirp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtolwlccpc.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtigjsxols.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtnveabfzc.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtotojdssg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtbnbzvswp.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtiyczvkga.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtuuxesdun.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtlmhtmejr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtfnfnzgmj.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtsrxglqrk.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtfjoduelp.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtkxqfbtin.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtwkqiaexc.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtzbpoasod.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtgpeeewjk.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtdjqcvxty.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgircpnn.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtvkknpkac.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtkokpytci.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtjwndyxxm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtooluyjcj.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtlrhaqqzu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtlebmmkie.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gthbwdajtv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcbevfzkf.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtitewypyg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtqbdezamt.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtqqxkuzst.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtrmipavqt.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtpvvjxphq.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtnghvprti.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtazsgvozo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtrncxltio.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtivptevhj.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtgqtxztpy.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcndwncd.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtmnksktrk.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtomladxsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtptfbepdw.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtilypprvg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtxioawlgd.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtsxbokwwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtljnwzjuu.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtcizuzpgt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtnxujhahe.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gttamelrro.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtfvfoaobz.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtqvjlaovb.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtpdqbemgn.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtuknuhjpd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnfshmxo.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgykgmyys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtgxxiodhg.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gttqujoifg.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtbocelwrj.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtqvgvfrta.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtmuokrcwb.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtvsizxwrq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtzetydbkl.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxmcvafz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtboxicdla.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtjvfhsgpz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtqrzvprba.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtyvckjumj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtoezvvslk.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtzxsnsrye.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtdhtsilwq.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtksuavpta.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtskichzof.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtdrkeutab.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtiqkqknjz.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtxsahtsqh.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtezihjqeq.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtpoviaput.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtghbgulaz.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtwwncqprn.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gtaxpghjvf.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtngtujswe.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtgnvysmkn.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtzlmesbvk.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtccwhuwxo.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtcwkqtrli.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtnwplprpu.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtbyhysgal.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtcmakuile.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtlgdpnjjr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtkcqvtcux.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtmihmadkc.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtjfxjmfoc.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtxkxhnzwq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtefcfudso.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtwrpzxmga.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtekyddfxb.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gtxnvdgple.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtrbyrdzll.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtwngwpfdr.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtjarghmtg.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtnamfmwci.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtmlbrjvdu.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtgfbiyqus.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuspoopz.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtcpcduede.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtjbdbxlrc.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtivmcyjsa.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtfjczqggw.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtcgcgrcyh.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtaedmuxrb.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtrxmejlnf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtwqegxckq.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtehuythra.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtgpsyoxhj.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtltkmhwjn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gttldenwxc.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtccokdpwd.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtqiyoiogi.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtjmbdbuql.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtlildkklu.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtyuzzbhwv.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyzwonlk.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtphijqnac.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtmecgdjrb.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtrcyjaqrn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtsyepxzmo.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtsrvxbzjj.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtgsyyhwid.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtwvjouwmz.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtpcdclans.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtxwpdpenh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtzdrjwyds.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gttoxcudtr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtffztadsp.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gtbxnwzrmh.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtgpfyzsgc.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtuvgkfyvh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtjwgftkke.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtmiduhjiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gteelaxxpk.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gttghsxohn.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtddresmct.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtrjjopwsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtaqptygux.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtgzgssvqo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtrcyjxmxr.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtmgizmsjx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtqhtxcuva.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisorejf.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtlxigayln.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtmixhayqq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtxvtutdur.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtasyjcimf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtrxgwtkmn.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtvmbuhaxt.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtalbhrngl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbdkfvxnr.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtkozsgopo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfbavpabh.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtcfuihiwg.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtrlwrfxqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtulytynfo.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtlivavxwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtmlruwkvb.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtvexwdutb.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gthoxpwmva.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtmzazwvcq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtytmhivyt.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtkdkdojai.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gttdkqqqtb.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtfrnnfcos.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtqcbhhrva.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtqhhecdrn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtccvenylr.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtjttkqngo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtvttouhrl.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtbytmdoae.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtmplgwyau.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtguqwkacd.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtbekgizjw.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtsasyubxa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtmururwdo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtnyrwjpxp.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtvnyacija.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtryqkxbqe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtdcfjuqsh.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtgkcljwgr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtkdvbynix.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtioddeoxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtkvurqmeg.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtedncmkea.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtatlloofy.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gthvmdondh.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvmhqyonf.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtelmtwwrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtbxhniiue.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtvmegngll.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gttfforrra.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtixnpunth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtlzzfvqdi.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtzxtoffku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtbuqmibte.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gtszxcmdme.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtrbyrrrpd.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtscfelvgy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtrkbvxphk.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtvqpgencc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtsszgjvqy.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtrbftyduz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtvmqestyr.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtfhcnwtht.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtyseulkwl.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtfzasbtcp.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtfcwafshf.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtoukikagn.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtkltuocfm.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtczdnamsr.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqpfkznr.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtschpohiu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtjigybyyq.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtpqpheblk.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtogeenhwh.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gtrkcboxwl.html

#endif
来源：http://dali.birdmap.top/Article/details/gtzfrpcttn.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtwdkgjzfr.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtwwlhivxx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtwtendwxa.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gtaxufynxd.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtlgjuxbgr.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtwozwtkql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtrufasocg.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtfrhxpwxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdtrtiqj.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtnqkuqdlt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtmrxndlib.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtflkwfocv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtxeukraid.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtjlaopaah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtmfkcexad.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtobbvkdqq.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtoayqejpr.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gtklwnidnq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtyqblndey.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtqyzowtzu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtpmlkhvyu.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtzvzhstvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtamrdahkf.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtkjjuontk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvomyrwdr.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtsqjyqele.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtpchpgryh.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtekyaixzn.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtdwkqkran.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtdxdtoweh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtcsliigjg.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwobzkpwz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtrteambrc.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtxqwaxsez.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtsgugyiza.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtyuvmiams.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtnamsgiju.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtnfbjngid.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gthcsidbdg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxhvqocu.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtespghmrc.html


<!-- 参考信息 -->