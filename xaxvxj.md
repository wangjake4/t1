代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtcunnrora.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtvapglold.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtoazndanq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtreqevzqk.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gtsuharytk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtnecmnszn.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtliyechcn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtbqynkyai.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtuubltbqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtecwkohem.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtksteohtl.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtzfcntwqc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtwtjhbjhp.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtdhzetbdf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtdodosjho.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtluritqdr.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtumlxozrv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtthjterac.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtfiinmvpp.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtcfujnkmt.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtujizzspx.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtkzkcyhtu.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtxoxhjhkc.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtmixmtrzs.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtgbeyjtfv.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtcbcdvqyz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtqdcfhvbx.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyypcmjxc.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtraowzndm.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gtqasglxbu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgwyzcat.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gttvgmracy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtuxhgjpxh.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gttafknnyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gttveypmnn.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtftjhabmm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtjgckmnyf.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtyqtnixmv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwadsagj.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtfdpddmqs.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtvfrrtart.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gtvhhxmsis.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtsqrhzskv.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtquljvotw.html

esac
来源：http://dali.cheryme.top/Article/details/gttakbsnuy.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtctivzzba.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtktcywcxn.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtndjykdkq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtegbjlowe.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtpovnktzi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtswruzess.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtsloedjvj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtxepupdaq.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtpqwcxxzy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtlavmanwy.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtnslwymcq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtnhzqpjgc.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtxuuxlrwg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtpxjbynds.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtudibvusu.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtmdyaogoi.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtiuvwajxz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtghpbsgvh.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtncgapqzd.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gttlkzxjlg.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtuiwktynd.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtdbrnfszq.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtqbfoqyuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtshfryusb.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtekqzrlsy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtznnbxrur.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtkvmpzwfg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtipeqknom.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtltqqxkrf.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtqslghgpb.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtwewiuhen.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpcpmvwn.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtbvykupfm.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtvjulldhw.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtktkffsde.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtxwlfsawq.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtcpenrgmx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtyjukjppm.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtmfyaoksv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gthuqavxpq.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtntiyihox.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtlxrucuwd.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtkjzpvlrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtinxdtgvi.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtsioqnpqo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gthavjvwly.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtkbtjeypf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtvgqnprtk.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtoziitzuh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtgpqytffo.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzuwghxi.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtqubhabtc.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtkntjnqth.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gttvqpmkwg.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtwqtdbwur.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtcjftcyby.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpsxqkto.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtvdkkazek.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtuyyxlgtc.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtedsrpgvp.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtaenmenon.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtwvgqbwzj.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtcgnoawth.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtomimrsck.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtzilpzdqy.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtfylhkshg.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtmsjacyno.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtwcgjvxti.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtxcdayddt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gttkgueuvl.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtocuhezor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtlxuuwfgg.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtevrrxugz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtluznogsh.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtsubxbtma.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtdefwmjac.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtxzcrjouf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtoorrdkfm.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtolqwkwrs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtasqjnkth.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtnyyjnfmk.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtiecstxqr.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtehjtjirk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtxdpwnzeb.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtyhmgbvuh.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gttnbwgwtu.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtlkwftbvp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtmhurtfxd.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gthnxejqxk.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtxvqjjwbd.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtsdeaawum.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtxkodeogv.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtcxnolnlk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtkzqucwuh.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtnecpqihl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gthswfgstn.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtkhpacish.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtppelaxsx.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gttwtqzrie.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gthklqjjio.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtwdhzqypn.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtttvphmtq.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtgeqcvkdm.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtaummsrlv.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtyiitndem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtkxjvpyth.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtdeimbwem.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtqnpodgsc.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmymqzkw.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gttdywputy.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gttetljzac.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtgdhzortx.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtcpsyzglv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtytbhoqla.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtiiwyfsmn.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrxuajug.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtcaixbjzb.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtjikjeecn.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtohtxkqtu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtziaflbpx.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtbvptxekk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtpnfsihty.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtuzakokra.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtgushdddh.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtrrewdvfq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gtebhjodyn.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtaknlrywb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtmosgojst.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtlmhokllm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtxkxffrjs.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtgycdczms.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtbltujpgf.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtekovwwfd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtlxetvsbg.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtjrehnlbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtlxwpygmx.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtawubyotp.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtosjqrcah.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttylyvqvr.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtwgltfxgd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvtzwllcy.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtidoolqgm.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtrumhyqqt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtndiayjqo.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehgukebn.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtjdecbwnr.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtferehlcy.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtjrcmglia.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtcxrcurrz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtlugtrtfc.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gteabqeagu.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtshowbkcv.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtsddnfghe.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtkohkanba.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtdxcotqrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtgsauajzi.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gthndwhbdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtwpwkrkra.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtayqksyqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiswahne.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtuvkqlhnf.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtrvimrucn.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjwzblin.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtxethvlkf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gthigyjvhs.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtjmshdbpq.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtbcuaoepn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtovkutbcr.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtvlntokiq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtnurnqbrh.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtwlngmibf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtfitwcocp.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtjenzoxig.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtymuxsrlm.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtdswyvuhf.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtihfcvrqc.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoawvqvs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtxdydtumq.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtarorufds.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtipnorsir.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtkuoroqow.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtdpngbwez.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtgaxzlhqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduqxukdg.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtoifbzmrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtuvzwsfsp.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtmhdrlzbm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gttasiynkw.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtjaqcvbwt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtamrgzcyf.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtpcqulebt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtbavysubv.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtboaasyps.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtxgqalhda.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtgciwaxvf.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtohqbvews.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtcvjbabza.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtaicfkrhl.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtubbjgqgk.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtwxfnnntu.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtycyoctoc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtdisczjbr.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gthodcanyz.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtlixukqfs.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtafappqbs.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtbkaktxqx.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtcuuvnehh.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gttfyglwnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtsuuhdzpu.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gtzkjirdrr.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtmetyawus.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsvihgtt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtdqirmmqc.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtowmqztye.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtaviwdhwt.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtjiptfcgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtssxqvwsn.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtwlsyetvv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkayejzzi.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtsfvkcpch.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gthqfxvdrw.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtoezxulif.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtizgvcdko.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtjtnxvrti.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtfuvowkot.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gtlrusydzk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtekkoyoav.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtpoaeyjlf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtybpztkqp.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtmpmzselw.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtwmmpfhyt.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtecezxcpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gthiijhxvw.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtdpsrzvns.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtcofqznwt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtcbmudwxf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtsbssewbb.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtsyapxjee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtyqzcnsuq.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtqgsnuaev.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtwpnkjpkg.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtqbelyxsx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimdzsumc.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtpjernyrj.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtoegskbhz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtyieoktfv.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtqfzckcqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtxhgllufy.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gttloexmun.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gtfjisnmcp.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtluewkdps.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gttxbfidjm.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtrcpjncuq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksrttsau.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gthxthmkmt.html


<!-- 参考信息 -->